<div align="center" style="padding-bottom: 1em;">
<img width="100px" align="center" src="https://avatars.githubusercontent.com/u/74017645?s=200&v=4">
</div>

# <div align="center">MaRDA Metadata Extractors: Discussions & Minutes</div>

<div align="center">


[![Documentation](https://badgen.net/badge/docs/marda-alliance.github.io/blue?icon=firefox)](https://marda-alliance.github.io/metadata_extractors/)

</div>

This repository contains organizational info for outcomes of the [MaRDA](https://www.marda-alliance.org/) working group (WG) focused on connecting and advancing interoperability of efforts on automated extraction of metadata from materials files.

**Contacts**:

- *[Matthew Evans](https://ml-evs.science), UCLouvain*
  (`matthew.evans[at]uclouvain.be`)
- *Peter Kraus, TU Berlin*
  (`peter.kraus[at]ceramics.tu-berlin.de`)
- *David Elbert, Johns Hopkins University* 
  (`elbert[at]jhu.edu`)
  

## Contributing

This working group is completely open.
If you would like to be added ot the mailing list please reach out to us over email, or just turn up at a meeting!

The GitHub discussions from the original working group are located here:

- [marda-alliance/metadata_extractors_schema](https://github.com/marda-alliance/metadata_extractors_schema)
- [marda-alliance/metadata_extractors_registry](https://github.com/marda-alliance/metadata_extractors_registry)
- [marda-alliance/metadata_extractors_api](https://github.com/marda-alliance/metadata_extractors_api)


## Organization & logistics


- We are still planning how the project will continue as the MaRDA Working Group comes to an end


The text below is taken from the initial working group proposal.

### Motivation

Enabling interoperability between experimental apparatus, software, scientists and informaticians requires a lot of plumbing.
This plumbing is often characterized as an **Extract-Transform-Load** (ETL) pipeline, whereby data is first extracted from some heterogeneous sources, transformed into a suitable format for the use case (querying, archival, further analysis) and then loaded onto a storage platform (a database, a filesystem, an archive repository, supplementary info for a publication).
Such pipelines are often opaque, not reproducible and not sufficiently modular to be reusable; these features penalize groups with fewer resources to devote to data management, leading to much duplicated effort on reimplementing parsers or extractors for different file types and transformed data models.

This working group aims to address these issues and promote FAIR practices by designing, creating and reusing software and infrastructure to streamline the process of describing ETL pipelines in such a way that they can be more broadly reused, and associated tooling for automated execution and discovery of said pipelines.
Following the name of the WG, it will primarily target the **Extraction** step, i.e., the literal parsing of unstructured data files, and the description of the output Transformed data model and encouragement of FAIR representations (c.f. the upcoming recommendations from MaRDA WG5).
This is a different approach from the typical target of creating a unifying output data schema; instead we will remain agnostic to the output format if it is sufficiently well-described in a machine-actionable manner.

