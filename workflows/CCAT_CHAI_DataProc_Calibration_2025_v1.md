# CCAT_CHAI_DataProc_SpectralAnalysis_2025_v1

## Overview

Daily workflow during the time data is being taken with CHAI. This workflow will be
active from mid 2025. This workflow will calibrate the raw data and create calibrated
spectra as well as auxiliary data products (Trec, Tsys, ...).

## Main Contacts for this workflow

- Christof Buchbender (buchbend@ph1.uni-koeln.de)
- ...

## Science Goals

This workflow will calibrate the individual spectra so that they can be used for data
quality assessments and reduced and gridded to create maps of the observed regions. 

## Instruments/Modules Involved

- LFA: In the beginning of CCAT operations only the "Low Frequency Array (LFA)" of CHAI
  will be active.

## Input Data

- Data Source: The raw data for CHAI will be `.fits` files containing the individual
  spectra.
- Data Acquisition: Daily during a CHAI campaign

## Processing Steps

1. Calibration of the raw data

## Computational Requirements



| Time Range | Estimated Storage per Batch | Cumulative Storage | Processing Power | Memory Requirements |
|------------|-----------------------------|--------------------|------------------|---------------------|
| 2025       | 4 TB                        |                    | Y GHz            | Z GB                |

_Note: Replace X, Y, Z with the appropriate values for storage, processing power, and memory respectively._

## One-off Workflow or Recurring Processes

This workflow is a recurring process that will be executed daily during a CHAI campaign.

## Output Data Products

The output data of this process will be parquet files containing the metadata,
calibrated spectra and auxiliary data products (Trec, Tsys, ...).

## Time Constraints

This workflow has to execute daily to ensure timely calibration and data quality
assessment of the CHAI data to get feedback on the achieved signal-to-noise ratio for
the different surveys and to spot potential problems with the instrument in the quality
assesment of the data.

## Concurracy

Do other workflows have to run parallel or connection to this one? E.g. other projects

- `CCAT_CHAI_Analysis_QA_2025_v1`  (Quality Assessment of the data after this workflow)
- `CCAT_CHAI_DataProc_Gridding_2025_v1` (Gridding of the data after this workflow)
- `CCAT_CHAI_Vis_QuickView_2025_v1` (Quick View Products for the newly taken data and the
  cumulative data set)

## Software Stack

This workflow will be implemented in python and makes use of the `calibrate` package
### Core Analysis Tools

- calibrate: https://github.com/ccatp/calibrate

### Data Processing Libraries

- Library 1: Description and function.
- Library 2: Description and function.

### Visualization Tools

- Tool 1: Description and usage in data presentation.
- Tool 2: Description and usage in data presentation.

### Auxiliary Software

- Software 1: Supporting role and purpose.
- Software 2: Supporting role and purpose.

### Compatibility Requirements

- List any compatibility requirements between different software tools (e.g., operating
  system constraints, inter-software dependencies).

## Future Enhancements

Ideas or plans for future updates to the workflow.

## Version History

- Version 1.0: Initial version.

---

Remember to update this document as the workflow evolves or as new requirements are identified.
