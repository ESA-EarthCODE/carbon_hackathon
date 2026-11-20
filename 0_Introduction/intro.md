# Carbon Hackathon

This repository contains resources for the online and in-person parts of the EarthCODE Hackathon, taking place from 30 November to 4 December.

The hackathon focuses on developing reusable data pipelines for carbon science. You will work in [DeepESDL](Workspace/workspace.md), access and combine data with [xcube](../1_Data_Access/xcube-data-acess.md), and adapt ideas from [EO-LINCS science cases](../1_Data_Access/eo-lincs.md).

## How the resources fit together

1. **Work in [DeepESDL](Workspace/workspace.md).** The platform provides the shared JupyterLab environment, compute, storage, and interactive data tools for the hackathon.
2. **Find and prepare data with [xcube](../1_Data_Access/xcube-data-acess.md).** Learn how xcube data stores provide a consistent way to access data and how xcube-multistore harmonises data from several sources.
3. **Develop a research idea with [EO-LINCS examples](../1_Data_Access/eo-lincs.md).** Use the project’s science cases and reusable workflows as starting points for your own question.

The [agenda](agenda.md) describes the sessions and dates. Meet the [organisers and instructors](instructors.md), and use the [EarthCODE Discourse forum](discourse.md) to ask questions and share findings.

## What we will work on

Work on your own research, explore the available data and tools, or develop a pipeline that others can understand and reuse. The [EO-LINCS examples](../1_Data_Access/eo-lincs.md) provide starting points spanning carbon fluxes, forest recovery, model–data relationships, and vegetation-model benchmarking; you are equally welcome to bring your own question.

## Suggested workflow

1. Register on the [DeepESDL EarthCode Hackathon 2026 Hub](https://workspace.deepesdl-earthcode-hackathon-2026.deepesdl-v2.eox.at/home) with your GitHub login and read the [DeepESDL platform guide](Workspace/workspace.md).
2. Browse the [xcube data-access guide](../1_Data_Access/xcube-data-acess.md) and one or two [EO-LINCS examples](../1_Data_Access/eo-lincs.md).
3. Join the introductions and EO-LINCS tutorial on 23 November, then develop your idea during the coworking days.
4. Choose a question, relevant variables, locations, and dates.
5. Bring initial results, questions, and feedback to the consolidation session on 25 November.
6. Continue refining your idea for the in-person hackathon from 30 November.



## Suggested focus areas


The four suggested paths are intended to help participants get started during the Hackathon. The science questions and proposed topics are not imposed or mandatory; they are simply starting points to provide scientific and technical directions, help teams shape their own scientific questions, formulate the activities and identify points of improvements.


| Nr | Challenge | Goal | Science questions |
|---|---|---|---|
| 1 | **Scientific reuse and scaling of EO-LINCS pipelines across regions and datasets** | Applying existing EO-LINCS pipelines to new datasets, environmental conditions and regions, including RECCAP-3 regions. | • **How easily can we reuse an existing EO-LINCS workflow in a new region or ecosystem?** What would need to change?<br><br>• **Where are the current gaps?** Are some ecosystems, environmental conditions or land-cover types not well represented by the existing workflows and datasets?<br><br>• **What additional data would help?** Which datasets could make EO-LINCS workflows more useful or transferable to other RECCAP-3 regions? |
| 2 | **Extracting site-specific information from available EO datasets** | Extracting site-specific information, combining products and developing new scientific analyses. | • **How can information from large cloud-native EO datasets be extracted for individual sites and networks** such as ICOS, FLUXNET or GEO-TREES?<br><br>• **How should the data be prepared?** What level of aggregation, harmonisation or standardisation would make the extracted information immediately useful?<br><br>• **What happens when we combine different datasets?** What problems arise from differences in spatial resolution, temporal coverage, formats, coordinate systems or metadata, and how could these be improved?<br><br>• **What additional in-situ observations would help answer the scientific question?** What currently makes it difficult to bring these data together with EO observations? |
| 3 | **Benchmarking data usability and accessibility across terrestrial carbon datasets** | Evaluating the practical usability of existing datasets and services from both user and producer perspectives. Test existing datasets and tools such as xcube-multistore, EarthCODE Catalogue, Sense4Fire and S24Amazonas and other community resources. | • **What potential topics can be addressed by applying available datasets?**<br><br>• **How easy is it to find the right data?** Can researchers discover datasets relevant to a particular scientific question without already knowing where they are?<br><br>• **What do we gain by combining datasets?** Which products work well together, and what new scientific information or applications could their combination provide?<br><br>• **Where are the biggest technical barriers?** Which datasets are particularly difficult or time-consuming to access, prepare or analyse?<br><br>• **What would make the datasets easier to use?** Are important metadata, documentation, examples or other supporting information missing? |
| 4 | **Best practices for the terrestrial carbon science community: FAIR data and workflows** | Explore how terrestrial carbon datasets and workflows can be improvement in terms of their documentation, format, so that they are FAIR, reusable and easier for scientists to work with. | • **What does usable and FAIR terrestrial carbon dataset look like?** Which criteria should we use to assess accessibility, interoperability and scientific usability?<br><br>• **What should data producers provide?** What metadata, documentation and access options would make cloud-native datasets easier to discover and reuse?<br><br>• **What is the minimum publication package?** What should accompany a dataset for another scientist to understand and reuse it confidently?<br><br>• **How can we make publication easier for scientists?** Which steps in preparing and publishing data could be simplified or automated?<br><br>• **How well does the current publication journey work?** Are the existing tools, tutorials and guidance sufficient for publishing through EarthCODE and the Open Science Catalogue, and where are the gaps?<br><br>• **How should data be prepared for cloud-native use?** What should producers do so their datasets can be readily used through xcube-multistore and related services? |

## Expected outcomes

By the end of the online event, teams are expected to **start prototyping or developing a reusable workflow**, **producing code or notebooks with initial scientific analyses** or visualisations. We encourage participants to **put their hands on the datastes and existing pipelines to get familiarity with the platform and identify gaps which may be adressed during the main event.** Valuable outcomes will include** identifying data gaps, interoperability or usability issues, technical bottlenecks, and missing documentation as well.** Teams and individuals should capture  main findings, recommendations, open questions and suggested next steps so that we can develop on that feedback before the main event but also after the Hackathon.
