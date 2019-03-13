Open Source Software Development Plan
=====================================

*This excerpt was taken directly from section 1.3 of the project proposal.*

### 1.3.1 Software development plan
In addition to generating notebooks for specific scientific use cases (Section 1.2), our team will continue to follow its strong track record in producing well-documented open source software. The online documentation for Xarray, Dask, and Jupyter, is already comprehensive and user friendly; any additional features will follow this established standard. All of these projects are currently being developed under licenses approved by the Open Source Initiative (OSI) and their code development is open source and hosted on Github.

#### 1.3.1.1 Earth science data information policy
We are aware that NASA’s policy is to "maximize access to data and to keep user costs as low as possible". This project will enhance access to data via tools that interface with NASA metadata repositories and follow best practices in cloud computing design to avoid unnecessary costs associated with moving and downloading raw data.

#### 1.3.1.2 ESDS open source software
In accordance with NASA requirements, all software developed in this proposal will be be made available via the open source Apache License 2.0. Distribution of the software developed as part of this proposal will be though the GitHub website. DOIs will be generated for all software releases via Zenodo which will be made incremental milestones in the development process.

#### 1.3.1.3 Use of 3rd party software
The software used in this project is open-source and is supported and developed through a combination of academic, commercial, foundation, and volunteer efforts. The Scientific Python ecosystem is also widely used in, and supported by, industry, particularly in the emerging field of Data Science (Muenchen, 2017).


#### 1.3.1.4 Leveraging past efforts
While the efforts described in this proposal are new and are not a continuation of a previously awarded NASA funding, this project is designed to leverage ongoing efforts by the complementary Pangeo-EarthCube project. The scientific use cases will enhance data analysis and management capabilities in ongoing NASA funding efforts including: (1) NASA’s "High Mountain Asia Project" (PI Arendt is also a PI also on this project), (2) NASA’s AIST "Climate risks in the water sector: Advancing the readiness of emerging technologies in climate downscaling and hydrologic modeling" (co-PI Gutmann is a PI is also a PI on this project), and (3) NASA’s AIST "Development of computational infrastructure to support hyper-resolution large-ensemble hydrology simulations from local to continental scales" (NCAR collaborator Martyn Clark is a PI on this project). NASA funding would enable major advancements to technologies advocated for by the Pangeo community. In particular, our project will extend Pangeo tools to the commercial cloud environment with a distinct focus on NASA datasets.

#### 1.3.1.5 Deploying technologies to EOSDIS
The technology built in this proposal is meant to work alongside current EOSDIS tools (e.g. CMR, GIBS), rather than to be directly incorporated into regular DAAC operations.

#### 1.3.1.6 Utilizing cloud computing resources
We will be deploying the tools developed in this project on Amazon AWS, although tools will be easily transferable to other commercial cloud computing options, such as Google Cloud and Microsoft Azure.

#### 1.3.1.7 Utilizing automated testing and continuous integration
The core Pangeo packages have grown out of the open-source software community. Each of the packages include robust test suites and utilize continuous integration. Likewise, the technology built as part of this package will implement full unit testing frameworks and continuous integration.