# bioinformatic-worfklow-idioms

**== IMPORTANT ==**

**this document is for initial brainstorming of this repository**

### Core/Initial Set of Idioms

- Two tasks that consume the same output
  - motivated from Nextflow
- Tasks that consume output from multiple tasks
  - motivated from a Nextflow question where we want to tasks output to the same channel, and a single downstream consumer.
- Scatter/gather
- Tasks that produce an unknown set of output
  - ex. chunk a BED file into equal # of bases across regions)
- Pipe tasks
  - define individual tasks, can we pipe them together to be joinly executed.
- Localization of data or co-computation
  - sometimes we want two or more tasks to be co-executed on the same instance to avoid having to push/pull data
- 
 
 
### Core/Initial Set of Workflow Languages

- Nextflow
- Snakemake
- WDL
- CWL
- Dagr

How do we differentiate between versions (ex. WDL specs, supported features across versions of Snakemake)?

### Initial Layout of Documentation

Format?

- Github markdown?
- Sphinx

Hosting?

- github.com diectly
- published to readthedocs.io

