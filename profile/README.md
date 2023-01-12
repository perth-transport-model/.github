# Perth Transport Model

The Perth Transport Model (PTM) is an [activity-based](https://tfresource.org/topics/Activity_based_models.html) transport planning modelling system of personal and business travel currently under development for the Greater Perth region of Western Australia. The PTM will be used to simulate the impacts of existing and proposed public policy and investment decisions on travel behaviour and patterns and their impact upon multimodal transport system performance in Greater Perth. Forecasts will be created using the PTM for 20-50 planning horizons under a variety of scenarios of future growth in the region. The PTM will replace the [Regional Operational Model v2.4](https://www.mainroads.wa.gov.au/globalassets/technical-commercial/technical-library/road-and-traffic-engineering/traffic-modelling/operational-modelling/guidelines-for-calibration-of-traffic-volumes-rom24-appendix-c.pdf) (ROM24) currently used by Main Roads Western Australia (MRWA) and the [Strategic Transport Evaluation Model](https://www.transport.wa.gov.au/mediaFiles/projects/DOT_P_Transport_Modelling_Guidelines_Activity_Centre_structure_plans.pdf) (STEM) used by the Department of Transport (DOT). The PTM will be developed using travel surveys conducted over the past several years, to include the [Perth Area Travel and Household Survey](https://www.mainroads.wa.gov.au/globalassets/projects-initiatives/transport-surveys/paths-information-sheet.pdf) (PATHS), conducted over four annual waves from 2018-2021, and the [Commercial Vehicle Survey](https://www.mainroads.wa.gov.au/globalassets/projects-initiatives/transport-surveys/cvs-information-sheet.pdf) (CVS) conducted in 2020-2022. MRWA is managing the development of the PTM, to include a contract with WSP Austalia for its implementation. The major components of the PTM include:

<img src="profile/ptm-high-level.png" width="75%">

> Please contact [Wes Soet](mailto:wesley.soet@mainroads.wa.gov.au) at MRWA for further information about the PTM and its development process, to include access to some of the resources listed below.

### Timeline

+ The impetus for the PTM stems from a [Transport Modelling Review](https://www.patrec.uwa.edu.au/__data/assets/pdf_file/0003/2578710/2014-Transport-Modelling-Review.pdf) undertaken by UWA's [Planning and Transport Research Centre](https://patrec.org/) in 2014. They recommended the development of a Perth LAnd and Transport INtegrated Urban Model (PLATINUM) to address complex and emerging issues facing Greater Perth. 
+ The PATHS and CVS were designed and tested in 2017-2019 to collect current data to be used in model development and application. The data collection for both surveys have been recently completed, and work is underway to finalise the datasets.
+ WSP prepared a _PTM System Design and Implementation Plan_ in 2020 that proposed the development of the PTM as a first step towards the PLATINUM vision, enabling immediate progress while further evaluation of land use modelling options and possibilities were undertaken by UWA and the WA Department of Planning, Land and Heritage (DPLH). The design of the PTM anticipates, but is not dependent upon, integration with land use models when they become operational in the future.
+ The development of the PTM began in the fall of 2022. An interim modeling system will be delivered in 2023, with final delivery of a revised modelling system in 2025.

### Team Resources

The following resources are available to PTM team members:

+ The [PTM Design Guide](https://github.com/rickdonnelly/ptm-design-guide) describes the high-level design of the PTM system, to include the donor modelling systems that will be adapted for Perth, data requirements for model implementation and testing, development guidelines and coding standards, and the system acceptance criteria.
+ The [paths](https://github.com/transportanalytics/paths) repository contains scripts for and outputs from analyses of the PATHS data.
+ The [cvs_redux](https://github.com/rickdonnelly/cvs_redux) respository contains scripts for and outputs from analyses of the CVS data. Note that the CVS data themselves must be obtained separately from MRWA and stored securely on a local machine that keeps them separate from this repository.
+ The [ptm-dev]() repository contains model development works in progress, organised by task and PTM component.
+ The [ptm-interim]() repository contains the code used to implement the interim PTM system and links to data buckets required to run it.
