# CCAT Workflow Naming Scheme

This document outlines the naming convention used for workflows at the CCAT observatory,
particularly for the CHAI and Prime-Cam instruments.

## Format

The naming scheme follows this format:

``` txt
CCAT_[ProjectCode]_[InstrumentCode]_[ProcessType]_[SpecificTask]_[ActiveYears]_[Version]
```

### Components

- **CCAT**: Fixed prefix indicating the CCAT observatory.
- **ProjectCode**: Code representing the project this workflow belongs to see the
  projects folder.
- **InstrumentCode**: Code representing the specific instrument.
  - `CHAI` for the CHAI instrument.
  - `PrimeCam` for the Prime-Cam instrument.
- **ProcessType**: Type of process. Examples include:
  - `DataProc` for Data Processing.
  - `Analysis` for Analysis tasks.
  - `Vis` for Visualization tasks.
- **SpecificTask**: A brief description of the task or process.
- **ActiveYears**: In which years will this workflow be active (e.g. `2025`, `2025-2026`)
- **Version**: A version number (e.g., `v1`, `v2.1`).

### Example Names

- `CCAT_P1_CHAI_DataProc_SpectralAnalysis_2025_v1`

### Updating Convention

- This naming scheme should be reviewed regularly and updated as necessary.
- Changes to the naming convention should be documented and communicated to all
  relevant team members.
