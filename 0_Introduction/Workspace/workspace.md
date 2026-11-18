# DeepESDL platform

[DeepESDL](https://earthsystemdatalab.net/)—the Deep Earth System Data Laboratory—is the working environment for the hackathon. It is a cloud-native platform for scalable, reproducible Earth-science workflows using harmonised, analysis-ready data cubes. Use it to explore data, develop and run notebooks, collaborate with your team, and share results.

## Get access

1. Open the [DeepESDL Hub](https://deep.earthsystemdatalab.net/).
2. Sign in with your GitHub account.
3. Open JupyterLab and choose an available Python environment.
4. Start with a notebook from the [example-notebook catalogue](https://earthsystemdatalab.net/guide/jupyterlab/notebooks/) or create your own.

If you have problems signing in or accessing resources, contact [Konstantin Ntokas](mailto:konstantin.ntokas@brockmann-consult.de).

## What you can use

- **JupyterLab** for notebooks, analysis, and sharing reproducible workflows.
- **xcube integration** for on-demand data access, processing, exploration, and visualisation. See the [xcube data-access guide](../../1_Data_Access/xcube-data-acess.md).
- **Scalable computing** with Dask-based processing and GPU support where available.
- **Shared team storage and S3 integration** for collaboration and intermediate results.
- **Visualisation tools**, including xcube Viewer in a notebook and as a dedicated service. A deployed example is the [DeepESDL Data Viewer](https://viewer.earthsystemdatalab.net/).
- **EarthCODE integration** to publish data and reproducible workflows.

## Storage

Choose storage based on the size and purpose of your files. Team storage is shared: all team members can change its contents, and it does not provide change tracking.

- **Personal workspace storage:** Use this for notebooks and small datasets. It has a soft limit of 50 GB; you will be notified if you exceed it.
- **Team shared storage:** Use the team’s 250 GB block storage to share notebooks, intermediate results, and small data files with collaborators.
- **Team S3 storage:** Use the team’s 250 GB S3 storage for data cubes and other larger cloud-friendly outputs, for example datasets to explore with xcube Viewer.

## Custom Conda environments

Create a custom environment when the standard kernels do not include a package you need. Follow the [DeepESDL guide for creating custom team Python environments](https://earthsystemdatalab.net/guide/jupyterlab/jupyterlab/#creating-custom-team-python-environment).

- **Personal environments** are visible only to you. They remain available across every team of which you are a member.
- **Team environments** are visible to all members of the team. They are also available to you across your teams.

## Useful links

- [Earth System Data Lab overview](https://earthsystemdatalab.net/)
- [DeepESDL user guide](https://earthsystemdatalab.net/guide/)
- [DeepESDL data overview](https://earthsystemdatalab.net/data/)
- [DeepESDL Hub](https://deep.earthsystemdatalab.net/)
- [Example notebooks](https://earthsystemdatalab.net/guide/jupyterlab/notebooks/)
- [Data viewer](https://viewer.earthsystemdatalab.net/)
