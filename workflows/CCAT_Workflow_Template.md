# Workflow Name

Use Naming Scheme from `CCAT_Workflow_Template.md` and store the file with the same name
in this folder.

## Dependent on

- Workflow Name 1
- Workflow Name 2

## Overview

Brief description of the workflow, its purpose, and its relevance to the observatory's
goals. Also outline for what time range these workflows needs to be active. This will
allow streamlining, hardware and software requirements and optimize the development. For
this scope we aim at very concise documents that include the major corner stones of the
workflows

## Contact Person

The contact person will maintain and take care for this workflow. The data center team
will work to implement the workflow. The contact person is responsible to define the
workflow and for providing the scientific analysis and reduction algorithms.

## Instruments/Modules Involved

- Instrument 1: Description and role.
- Instrument 2: Description and role.

## Input Data

- Data Source: Description of the raw data, including format and initial volume.
- Data Acquisition: How often is the data is collected.

## Processing Steps

Very brief overview what will be done to the data.

1. Step One: Brief description.
2. Step Two: Brief description.
   - [ ] Additional notes or sub-steps.
3. Step Three: Brief description.


## Computational Requirements

Estimate the computational requirements for one run of this workflow as best as you can.
For daily workflows that process the incoming raw data under normal operations estimate
the computational needs for each "batch" of data that comes in and give the cumulative
storage size for the final raw data once all of the data for this workflow has been
taken.  

Please update these estimates when better guesses become available. This is one of the
most important part of this workflow definition for the data center team to estimate the
computational requirements in time for hardware proposals.

- Estimated storage needs for each "batch" and "cumulative sum"
- Processing power required.
- Memory requirements.

## Workflow Resource Requirements

| Time Range      | Estimated Storage per Batch | Cumulative Storage | Processing Power | Memory Requirements |
|-----------------|-----------------------------|--------------------|------------------|---------------------|
| Time Range 1    | X TB                        | X TB               | Y GHz            | Z GB                |
| Time Range 2    | X TB                        | X TB               | Y GHz            | Z GB                |
| Time Range 3    | X TB                        | X TB               | Y GHz            | Z GB                |

_Note: Replace X, Y, Z with the appropriate values for storage, processing power, and
memory respectively._ _Note: For Time Range use the format_ `YYYY-YYYY` _for years or_
`YYYY-MM-DD-YYYY-MM-DD` _for more fine grained definition._

## One-off Workflow or Recurring Processes

Is this a workflow that will be executed one time or not very often (e.g. yearly) or is
this a recurring process (e.g. "daily data processing"). Details about the frequency of
this workflow (e.g. how often will this be executed), for example: "each time new data
is taken (how often will this be)" "daily", "monthly", "3 days a month", ...

## Output Data Products

Describe the Output Data Products. File format, size, number of files.

- Product One: Description and specifications.
- Product Two: Description and specifications.


## Time Constraints

Details on any time-sensitive aspects of the workflow. How fast after data taking does
this workflow has to be executed after data has been taken.

## Concurrency

Do other workflows have to run parallel to this one? E.g. other projects 

- Workflow Name 1
- Workflow Name 2

## Software Stack

Outline the software tools, libraries, and frameworks expected to be used in the
workflow. Include versions if specific ones are required. This is to get an overview of
the software stack that will have to be supported and/or to streamline the development
across workflows to use a uniform software stack where possible. For the start this can
be brief. Please just name the tools and packages.

### Core Analysis Tools

- Tool 1: Description and role in the analysis.
- Tool 2: Description and role in the analysis.

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
- Version 1.1: Changes made with dates and reasons.

---

Remember to update this document as the workflow evolves or as new requirements are
identified.
