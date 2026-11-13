# Carbon Hackathon

This repository contains the resources for the online and in-person part of the EarthCODE Hackathon 30 Nov - 04 Dec 2026. The focus is on contributing to data pipelines developed within ESA Project [EO-LINCS](https://www.eo-lincs.org/) _(Earth Observation, Local and Integrated data eNquiry for Terrestrial Carbon Science)_. for carbon-science data access and workflows, and [DeepESDL / Earth System Data Lab](https://earthsystemdatalab.net/) as the working platform.

## Start here

| Resource | What you will find |
| --- | --- |
| [Agenda](0_Introduction/agenda.md) | Sessions for the online hackathon on the 23rd, 25th Nov |
| [Organisers and instructors](0_Introduction/instructors.md) | Hackathon team and session leads. |
| [Discussion forum](0_Introduction/discourse.md) | EarthCODE Discourse for questions, ideas, and shared findings. |
| [EO-LINCS](0_Introduction/eo-lincs.md) | Project background, data-access tools, and carbon-science examples. |
| [DeepESDL platform](0_Introduction/Workspace/workspace.md) | Platform overview, access, and getting started in JupyterLab. |

## About
The intention of this Hackathon is to bring together the data producers and scientific users from various terrestrial carbon projects to test the practical usability of the datasets, benchmarking data access and extraction workflows, while exploiting as well the publication process and implementation of FAIR open science into [EarthCODE](https://earthcode.esa.int/). Further, it aims to test how easy it is to re-use these data for creating other uncertainty aware carbon data products and workflows to improve EO, ICOS, or modelling datasets for carbon-budget assessments and carbon monitoring in various scales from small areas of interest to regional scale. The data access and processing pipelines will be facilitated by the open source tools and workfows, such as those developed within ESA Project EO-LINCS. EO-LINCS was launched to promote a community effort towards an **enhanced multi-mission assessment of the terrestrial carbon cycle at resolutions in space and time** compatible with decision making by **improving the access to the Earth Observation (EO) data for the wider carbon scientific community.**

## What we will work on

Work on your own research, explore the available data and tools, or develop a pipeline that others can understand and reuse. EO-LINCS provides examples spanning carbon fluxes, forest recovery, model–data relationships, and vegetation-model benchmarking. These are starting points for choosing a question; participants are encouraged to bring their own ideas too. See the [EO-LINCS science cases](https://www.eo-lincs.org/science-cases.html) and the [Agenda](0_Introduction/agenda.md) for more.

## Suggested workflow

1. Read the [platform guide](0_Introduction/Workspace/workspace.md) and confirm your access before the first session.
2. Join the introductions and EO-LINCS tutorial on the 23rd Nov.
3. Choose a question and a set of relevant variables, locations, and dates.
4. Work on selected topic individually or in the team on 24-27th Nov.
5. Bring results, questions, and feedback to the consolidation session on the 25th Nov.
6. Continue working on your idea or choose another topic and team during the in-person hackathon starting on the 30th Nov.

* *Practical information related to in-person event will be provided in separate communication from ESA Conference Bureau*


## Suggested focus areas

The four suggested paths are intended to help participants get started during the Hackathon. The science questions and proposed topics are not imposed or mandatory; they are simply starting points to provide scientific and technical directions, help teams shape their own scientific questions, formulate the activities and identify points of improvements.<br>


| Nr | Challenge | Goal | Science questions |
|---|---|---|---|
| 1 | **Scientific reuse and scaling of EO-LINCS pipelines across regions and datasets** | Applying existing EO-LINCS pipelines to new datasets, environmental conditions and regions, including RECCAP-3 regions. | • **How easily can we reuse an existing EO-LINCS workflow in a new region or ecosystem?** What would need to change?<br><br>• **Where are the current gaps?** Are some ecosystems, environmental conditions or land-cover types not well represented by the existing workflows and datasets?<br><br>• **What additional data would help?** Which datasets could make EO-LINCS workflows more useful or transferable to other RECCAP-3 regions? |
| 2 | **Extracting site-specific information from available EO datasets** | Extracting site-specific information, combining products and developing new scientific analyses. | • **How can information from large cloud-native EO datasets be extracted for individual sites and networks** such as ICOS, FLUXNET or GEO-TREES?<br><br>• **How should the data be prepared?** What level of aggregation, harmonisation or standardisation would make the extracted information immediately useful?<br><br>• **What happens when we combine different datasets?** What problems arise from differences in spatial resolution, temporal coverage, formats, coordinate systems or metadata, and how could these be improved?<br><br>• **What additional in-situ observations would help answer the scientific question?** What currently makes it difficult to bring these data together with EO observations? |
| 3 | **Benchmarking data usability and accessibility across terrestrial carbon datasets** | Evaluating the practical usability of existing datasets and services from both user and producer perspectives. Test existing datasets and tools such as xcube-multistore, EarthCODE Catalogue, Sense4Fire and S24Amazonas and other community resources. | • **What potential topics can be addressed by applying available datasets?**<br><br>• **How easy is it to find the right data?** Can researchers discover datasets relevant to a particular scientific question without already knowing where they are?<br><br>• **What do we gain by combining datasets?** Which products work well together, and what new scientific information or applications could their combination provide?<br><br>• **Where are the biggest technical barriers?** Which datasets are particularly difficult or time-consuming to access, prepare or analyse?<br><br>• **What would make the datasets easier to use?** Are important metadata, documentation, examples or other supporting information missing? |
| 4 | **Best practices for the terrestrial carbon science community: FAIR data and workflows** | Explore how terrestrial carbon datasets and workflows can be improvement in terms of their documentation, format, so that they are FAIR, reusable and easier for scientists to work with. | • **What does usable and FAIR terrestrial carbon dataset look like?** Which criteria should we use to assess accessibility, interoperability and scientific usability?<br><br>• **What should data producers provide?** What metadata, documentation and access options would make cloud-native datasets easier to discover and reuse?<br><br>• **What is the minimum publication package?** What should accompany a dataset for another scientist to understand and reuse it confidently?<br><br>• **How can we make publication easier for scientists?** Which steps in preparing and publishing data could be simplified or automated?<br><br>• **How well does the current publication journey work?** Are the existing tools, tutorials and guidance sufficient for publishing through EarthCODE and the Open Science Catalogue, and where are the gaps?<br><br>• **How should data be prepared for cloud-native use?** What should producers do so their datasets can be readily used through xcube-multistore and related services? |

## Expected outcomes

By the end of the online event, teams are expected to **start prototyping or developing a reusable workflow**, **producing code or notebooks with initial scientific analyses** or visualisations. We encourage participants to **put their hands on the datastes and existing pipelines to get familiarity with the platform and identify gaps which may be adressed during the main event.** Valuable outcomes will include** identifying data gaps, interoperability or usability issues, technical bottlenecks, and missing documentation as well.** Teams and individuals should capture  main findings, recommendations, open questions and suggested next steps so that we can develop on that feedback before the main event but also after the Hackathon.

