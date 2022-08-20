# STM32H747I-DISCO

## Dual-Core Changes

This TouchGFX Board Setup (TBS) supports the dual-core functionality of the STM32H747I-DISCO.
For this reason, it is important to understand that there are two separate sub-projects for each compiler:
- A CM4 project
- A CM7 project

Since TouchGFX is running on the CM7, its code is located within the CM7 folder inside the project structure:

- 📁 CM4
    - 📁Core
- 📁 CM7
    - 📁 Core
    - 📁 TouchGFX


The CM4 and CM7 sub-project are split up as below:
- 📁 STM32CubeIDE
    - 📁 CM4
    - 📁 CM7
