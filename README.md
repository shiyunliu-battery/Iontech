Welcome to our repository of open-source datasets and resources in the fields of battery monitoring and modeling! This platform serves as a comprehensive hub for researchers, engineers, and enthusiasts to access high-quality datasets, tools, and articles that empower advancements in battery technologies.

We extend our gratitude to the original publishers and contributors of these datasets, whose efforts and generosity enable the broader community to build upon their work. Explore and contribute to foster collaboration and innovation in the energy storage domain.

<img width="1024" height="575" alt="Battery_dataset_Shiyun Liu" src="https://github.com/user-attachments/assets/a5a94891-7dc1-40df-9cc0-14b69698baa6" />

---
## Available Datasets

### 1. Multi-year field measurements of home storage systems and their use in capacity estimation
The ISEA / CARL of RWTH Aachen University measured 21 private home storage systems in Germany over up to eight years from 2015 to 2022. All these storage systems are combined with residential photovoltaic systems to increase self-consumption. The measured quantities published are system-level battery current, voltage, power, battery pack housing temperature, and room temperature. The sample rate is one second. The dataset consists of 106 system years, 14 billion data points, and 1,270 monthly files stored in 21 system folders.
- **Link**: [Download Dataset](https://zenodo.org/records/12091223)
- **Related Articles**:
  - [Multi-year field measurements of home storage systems and their use in capacity estimation](https://www.nature.com/articles/s41560-024-01620-9#data-availability)
  - [Capacity estimation of home storage systems using field data](https://www.nature.com/articles/s41560-024-01662-z)
  - [Battery Charts](https://battery-charts.rwth-aachen.de/main-page/)

### 2. Lithium-Ion Battery Field Data: 28 LFP battery systems with 8 cells in series, up to 5 years of operation
This data set contains data from 28 portable 24V lithium iron phosphate (LFP) battery systems with approximately 160Ah nominal capacity. Each system's specific use case is unknown, but battery systems of this size are typically used as power sources for recreational vehicles, solar energy storage, and more.

All battery systems in this data set showed some form of unsatisfactory behavior and were returned to the manufacturer. Many reasons can cause a consumer to return a battery to the manufacturer for maintenance. The user's individual decisions may be motivated by personal judgment, BMS warnings, or customer support advice. This data set comprises a very small fraction of batteries sold of this version. Therefore, this data set is biased and not representative of the operational data of the entire population of this system version. An improved version replaced this battery system type. The battery system manufacturer provided the data set for this study and allowed its open-source release under the condition of anonymity.

Each battery system consists of 8 prismatic cells in series. Each system has one load current sensor, and each cell has one voltage sensor. The four temperature sensors are placed between adjacent cells, i.e., each temperature sensor is shared by two cells. Furthermore, the battery systems have active cell balancing. The available measurements vary from a single month to five years. Consequently, the number of data rows per system varies from several thousand to millions, depending on the duration of battery operation. The data set contains a total of 133 million rows of measurements.
- **Link**: [Download Dataset](https://zenodo.org/records/13715694)
- **Related Articles**:
  - [Gaussian Process-based Online Health Monitoring and Fault Analysis of Lithium-Ion Battery Systems from Field Data Cell Report Physical Science](https://www.cell.com/cell-reports-physical-science/fulltext/S2666-3864(24)00563-0?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2666386424005630%3Fshowall%3Dtrue)

### 3. Battery Failure Databank
The Battery Failure Databank features data collected from hundreds of abuse tests conducted on commercial lithium-ion batteries. Methods of abuse include nail penetration, thermal abuse, and internal short-circuiting.

This databank provides the heat output from cells undergoing thermal runaway, the breakdown of heat from the cell casing and its ejected contents, as well as the mass of the cells before and after thermal runaway and the quantity of mass ejected from the cell. The databank also organizes the stored data for understanding test-to-test variability for each cell type and trigger mechanism combination.

Additionally, most tests feature associated high-speed X-ray radiography videos for review alongside the data.
- **Link**: [Battery Failure Databank](https://www.nrel.gov/transportation/battery-failure.html)
- **Related Articles**:
  - [Predicting the heat release variability of Li-ion cells under thermal runaway with few or no calorimetry data](https://www.nature.com/articles/s41467-024-52653-3)
  - [The battery failure databank: Insights from an open-access database of thermal runaway behaviors of Li-ion cells and a resource for benchmarking risks](https://www.sciencedirect.com/science/article/pii/S0378775324000570?via%3Dihub)
  - [Decoupling of heat generated from ejected and non-ejected contents of 18650-format lithium-ion cells using statistical methods](https://www.sciencedirect.com/science/article/pii/S0378775318312205?via%3Dihub#sec5)
  - [Modelling and experiments to identify high-risk failure scenarios for testing the safety of lithium-ion cells](https://www.sciencedirect.com/science/article/pii/S0378775319300874?via%3Dihub#abs0010)
  - [Characterising thermal runaway within lithium-ion cells by inducing and monitoring internal short circuits](https://pubs.rsc.org/en/content/articlelanding/2017/ee/c7ee00385d)
  - [Identifying the Cause of Rupture of Li-Ion Batteries during Thermal Runaway](https://onlinelibrary.wiley.com/doi/10.1002/advs.201700369)
  - [Tracking Internal Temperature and Structural Dynamics during Nail Penetration of Lithium-Ion Cells](https://iopscience.iop.org/article/10.1149/2.1501713jes)

### 4. Second-life lithium-ion battery aging dataset based on grid storage cycling

This dataset accompanies the data article "Second-life lithium-ion battery aging dataset based on grid storage cycling" and contains second-life experimental data collected at Stanford Energy Control Lab for six NMC cells cycled using residential and commercial synthetic duty cycles. The data is shared in a .zip format. Please refer to the publication accompanying the dataset to get further details.
- **Link**: [Download Dataset](https://osf.io/8jnr5/)
- **Related Articles**:
  - [Second-life lithium-ion battery aging dataset based on grid storage cycling](https://www.sciencedirect.com/science/article/pii/S2352340924010084?via%3Dihub)


### 5. Dataset of lithium-ion battery formation and structured aging cycling data
The dataset includes raw formation data and structured aging cycling data processed by TRI BEEP. The BEEP structured data features interpolated cycling data with a manageable data size and cycle summaries. This dataset enables insights into the role of electrode utilization in extending battery cycle life.
- **Link**: [Download Dataset](https://data.matr.io/8/)
- **Related Articles**:
   - [Data-driven analysis of battery formation reveals the role of electrode utilization in extending cycle life](https://www.cell.com/joule/abstract/S2542-4351(24)00353-2)


### 6. Full factorial design of experiments dataset for parallel-connected lithium-ion cells
 This dataset includes experimental data from lithium-ion battery parallel-connected modules. Conducted at the Stanford Energy Control Laboratory, it employs a comprehensive full factorial design of experiments (DOE) on ladder-configured parallel strings. It investigates 54 test conditions, varying by temperature, cell-to-cell interconnection resistance, cell chemistry, and aging levels. Measurements include individual cell current and temperature distributions, enabling detailed analyses of cell-to-cell variations and their impact on module performance. Cell characterization data for NCA and NMC cells are also included.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/zh58byr53c/1)
- **Related Articles**:
  - [Unveiling the performance impact of module level features on parallel-connected lithium-ion cells via explainable machine learning techniques on a full factorial design of experiments](https://www.sciencedirect.com/science/article/pii/S2352152X24003670?via%3Dihub)


### 7. Lithium-ion battery aging dataset based on electric vehicle real-driving profiles
This dataset contains aging data of lithium-ion battery cells subjected to a typical electric vehicle discharge profile and periodic diagnostic tests. Collected over 28 months at Stanford Energy Control Laboratory, it includes tests for INR21700-M50T cells using Urban Dynamometer Driving Schedule (UDDS) discharge and Constant Current (CC)-Constant Voltage (CV) charging protocols. The dataset monitors capacity, Hybrid Pulse Power Characterization (HPPC), and Electrochemical Impedance Spectroscopy (EIS) to characterize battery aging under real-world driving conditions.
- **Link**: [Download Dataset](https://osf.io/qsabn/?view_only=2a03b6c78ef14922a3e244f3d549de78)
- **Related Articles**:
  - [Lithium-ion battery aging dataset based on electric vehicle real-driving profiles](https://www.sciencedirect.com/science/article/pii/S2352340922002062?via%3Dihub)
  - [Domain knowledge-guided machine learning framework for state of health estimation in Lithium-ion batteries](https://www.nature.com/articles/s44172-024-00304-2#Abs1)


### 8. Experimental data of lithium-ion batteries under galvanostatic discharge tests at different C-rates and temperatures
This dataset contains experimental data for three lithium-ion batteries tested under galvanostatic discharge at various C-rates and operational temperatures. Using the Arbin system, the dataset provides detailed measurements of voltage, current, and battery skin temperature, with ambient temperature controlled via a thermal chamber. It enables analyses of battery performance under varying charge-discharge rates and temperature conditions.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/kxsbr4x3j2/2)
- **Related Articles**:
  - [Experimental data of lithium-ion batteries under galvanostatic discharge tests at different rates and temperatures of operation](https://www.sciencedirect.com/science/article/pii/S2352340921001785?via%3Dihub)



### 9. Increasing generalization capability of battery health estimation using continual learning approach
These datasets contain data from different battery types (pouch and prismatic) aged under various temperatures and loading profiles. The data includes partial Q curves during charging, capacities, and state-of-health (SOH) curves normalized for verification. The dataset also incorporates information from non-accelerated battery degradation experiments, with detailed raw data for Dataset 5 provided for further analysis.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/n3b54nsw8m/9)
- **Related Articles**:
  - [Increasing generalization capability of battery health estimation using continual learning](https://www.sciencedirect.com/science/article/pii/S266638642300588X#abs0020)



### 10. EV field datasets (Tsinghua)
 Three real-world, large-scale electric vehicle datasets collected from 464 EVs of 3 different types, including over 1.2 million charging snippets. The dataset provides insights into real-world electric vehicle charging behaviors and patterns.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/mcsh4hnb8b/1)



### 11. Experimental degradation study of a commercial lithium-ion battery
This dataset contains data from the aging of 196 commercial lithium-ion cells with silicon-doped graphite anode and nickel-rich NCA cathode. The cells were subjected to a wide range of calendar and cyclic aging conditions, with periodic check-ups performed at a controlled temperature of 20°C. The dataset reveals insights into the effects of aging conditions on battery degradation, providing a comprehensive view of aging patterns.
- **Link**: [Download Dataset](https://mediatum.ub.tum.de/1713382)
- **Related Articles**:
  - [Experimental degradation study of a commercial lithium-ion battery](https://www.sciencedirect.com/science/article/pii/S0378775322014756#d1e1359)



### 12. Attention towards chemistry agnostic and explainable battery lifetime prediction
This dataset contains pre-trained model weights from the ARCANA framework, including models trained and fine-tuned on different battery chemistries, such as lithium-ion and sodium-ion cells. It provides resources for explainable battery lifetime prediction across various chemistries.
- **Link**: [Download Dataset](https://zenodo.org/records/10293072)
- **Related Articles**:
  - [Attention towards chemistry agnostic and explainable battery lifetime prediction](https://www.nature.com/articles/s41524-024-01286-7)



### 13. Underlying dataset for battery pack degradation
This dataset contains raw and processed data, as well as analysis codes, used to investigate aging in parallel-connected lithium-ion battery packs under thermal gradients. The dataset supports research into the degradation behaviors of battery packs and the effects of thermal gradients.
- **Link**: [Download Dataset](https://zenodo.org/records/10207731)
- **Related Articles**:
  - [Degradation in parallel-connected lithium-ion battery packs under thermal gradients](https://www.nature.com/articles/s44172-023-00153-5#Abs1)



### 14. NASA Battery Data Set
A dataset of lithium-ion battery experiments, including charging and discharging at different temperatures. It also records impedance as a damage criterion, providing data for studying battery prognostics and health management.
- **Link**: [Download Dataset](https://phm-datasets.s3.amazonaws.com/NASA/5.+Battery+Data+Set.zip)
- **Related Articles**:
  - [A framework for Li-ion battery prognosis based on hybrid Bayesian physics-informed neural networks](https://www.nature.com/articles/s41598-023-33018-0#data-availability)



### 15. Randomized Battery Usage
This dataset features batteries cycled with randomly generated current profiles. Reference charging and discharging cycles are performed periodically to provide benchmarks for battery state of health.
- **Link**: [Download Dataset](https://phm-datasets.s3.amazonaws.com/NASA/11.+Randomized+Battery+Usage+Data+Set.zip)
- **Related Articles**:
  - [Adaptation of an electrochemistry-based Li-ion battery model to account for deterioration observed under randomized use](https://www.papers.phmsociety.org/index.php/phmconf/article/view/2490)
  - [A framework for Li‑ion battery prognosis based on hybrid Bayesian physics‑informed neural networks](https://www.nature.com/articles/s41598-023-33018-0)



### 16. HIRF Battery Data Set
This dataset contains battery data collected from experiments on the Edge 540 Aircraft in a HIRF (High-Intensity Radiated Field) Chamber, providing insights into battery performance under unique testing conditions.
- **Link**: [Download Dataset](https://phm-datasets.s3.amazonaws.com/NASA/15.+HIRF+Battery+Data+Set.zip)
- **Related Articles**:
  - [Verification of a remaining flying time prediction system for small electric aircraft](https://papers.phmsociety.org/index.php/phmconf/article/view/2571)



### 17. Small Satellite Power Simulation
This dataset includes data from simulated experiments on small satellite BP930 batteries using the MACCOR system. It provides valuable insights into the battery performance for small satellite missions.
- **Link**: [Download Dataset](https://data.nasa.gov/download/cpqc-ztjh/application%2Fzip)
- **Related Articles**:
  - [A battery certification testbed for small satellite missions](https://ieeexplore.ieee.org/abstract/document/7356483)



### 18. Accelerated Battery Life Testing
 This dataset includes accelerated lifecycle data for Li-ion battery packs composed of two 18650 cells. It covers various loading conditions, including constant and random loading levels, as well as second-life battery pack cycling.
- **Link**: [Download Dataset](https://data.nasa.gov/download/xg3n-ngei/application%2Fzip)
- **Related Articles**:
  - [Prognosis of Li-ion Batteries Under Large Load Variations Using Hybrid Physics-Informed Neural Networks](https://papers.phmsociety.org/index.php/phmconf/article/view/3463)
 


### 19. A cross-scale framework for evaluating flexibility values of battery and fuel cell electric vehicles
The dataset for this paper is currently unavailable.
- **Link**: [Code Repository](https://github.com/macroenergy/Dolphyn.jl)
- **Related Articles**:
  - [A cross-scale framework for evaluating flexibility values of battery and fuel cell electric vehicles](https://www.nature.com/articles/s41467-023-43884-x#code-availability)



### 20. Lithium Inventory Tracking as a Nondestructive Battery Evaluation and Monitoring Method
- **Description**: Twelve datasets containing charge and discharge cycles of Li–LixNi0.8Mn0.1Co0.1O2 (NMC 811) cells, under various formulations, configurations, and testing conditions. This dataset supports nondestructive evaluation methods and lithium inventory tracking as a battery monitoring technique.
- **Link**: [Download Dataset](https://osf.io/2w4k3/)
- **Related Articles**:
  - [Lithium inventory tracking as a non-destructive battery evaluation and monitoring method](https://www.nature.com/articles/s41560-024-01476-z)



### 21. Probability Distributed Equivalent Circuit Model
This dataset supports the development of a physically motivated voltage hysteresis model for lithium-ion batteries. The model leverages probability distributed equivalent circuits to enhance accuracy in performance predictions.
- **Link**: [Download Dataset](https://zenodo.org/records/10852930)
- **Related Articles**:
  - [A physically motivated voltage hysteresis model for lithium-ion batteries using a probability distributed equivalent circuit](https://www.nature.com/articles/s44172-024-00221-4)



### 22. GIC/NMC Solar Battery Synthetic Data
This dataset contains more than 700,000 unique voltage vs. capacity curves, generated with slightly varied cell parameters to account for cell-to-cell variations. It includes separate datasets for training and validation.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/rg8b2k2k28/1)
- **Related Articles**:
  - [Data-driven direct diagnosis of Li-ion batteries connected to photovoltaics](https://www.nature.com/articles/s41467-023-38895-7)



### 23. Data-driven Capacity Estimation of Commercial Lithium-Ion Batteries from Voltage Relaxation
Experimental cycling data for three commercial 18650 type batteries (NCA, NCM, and NCM+NCA chemistries). The dataset provides cycling data, impedance measurements, and detailed descriptions of voltage relaxation tests.
- **Link**: [Download Dataset](https://zenodo.org/records/6405084)
- **Related Articles**:
  - [Data-driven capacity estimation of commercial lithium-ion batteries from voltage relaxation](https://www.nature.com/articles/s41467-022-29837-w)



### 24. Impedance-Based Forecasting of Battery Performance Amid Uneven Usage
Dataset of 88 commercial lithium-ion coin cells cycled under multistage constant current charging/discharging. Currents were randomly changed between cycles to simulate realistic usage patterns.
- **Link**: [Download Dataset](https://zenodo.org/records/6645536)
- **Related Articles**:
  - [Impedance-based forecasting of lithium-ion battery performance amid uneven usage](https://www.nature.com/articles/s41467-022-32422-w)



### 25. Identifying Degradation Patterns of Lithium-Ion Batteries from Impedance Spectroscopy Using Machine Learning
This dataset supports machine learning-based identification of degradation patterns in lithium-ion batteries through impedance spectroscopy analysis.
- **Link**: [Download Dataset](https://zenodo.org/records/3633835)
- **Related Articles**:
  - [Identifying degradation patterns of lithium-ion batteries from impedance spectroscopy using machine learning](https://www.nature.com/articles/s41467-020-15235-7)



### 26. Data-Driven Prediction of Battery Cycle Life Before Capacity Degradation
Dataset supporting the prediction of battery cycle life prior to significant capacity degradation. The data enables early detection and modeling for lithium-ion battery lifecycle management.
- **Link**: [Download Dataset](https://data.matr.io/1/)
- **Related Articles**:
  - [Data-driven prediction of battery cycle life before capacity degradation](https://www.nature.com/articles/s41560-019-0356-8)



### 27. Physics-Informed Neural Network for Lithium-Ion Battery Degradation Stable Modeling and Prognosis
This dataset includes data for 55 nickel-cobalt-manganese (NCM) 18650 batteries tested under six different charging and discharging strategies. The data supports physics-informed neural network modeling for stable degradation analysis.
- **Link**: [Download Dataset](https://zenodo.org/records/10963339)
- **Related Articles**:
  - [Physics-informed neural network for lithium-ion battery degradation stable modeling and prognosis](https://www.nature.com/articles/s41467-024-48779-z)


### 28. Real-Time Personalized Health Status Prediction of Lithium-Ion Batteries Using Deep Transfer Learning
A dataset containing 77 LFP/graphite cells tested under identical charge protocols but varying discharge protocols. The data supports real-time health prediction using deep transfer learning techniques.
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/nsc7hnsg4s/2)
- **Related Articles**:
  - [Real-time personalized health status prediction of lithium-ion batteries using deep transfer learning](https://pubs.rsc.org/en/content/articlehtml/2022/ee/d2ee01676a)



### 29. Prognosis of Multivariate Battery State of Performance and Health via Transformers
This dataset contains processed files for reproducing results in multivariate battery state prediction using transformers. It includes datasets for lithium-iron-phosphate fast charging and six cathode chemistries.
- **Link**: [Download Dataset](https://www.materialsdatafacility.org/detail/spacetimeformer_battery_v1.2)
- **Related Articles**:
  - [Prognosis of Multivariate Battery State of Performance and Health via Transformers](https://arxiv.org/abs/2309.10014)
  - [Multivariate prognosis of battery advanced state of health via transformers](https://www.cell.com/cell-reports-physical-science/fulltext/S2666-3864(24)00177-2)



### 30. Battery Aging Modes Across NMC
A dataset of 44 NMC/Gr single-layer pouch cells, including data on cycle-by-cycle capacity, Coulombic efficiency, and end-of-charge/discharge voltages. The dataset also includes code for battery aging mode classification.
- **Link**: [Download Dataset](https://zenodo.org/records/7250553)
- **Related Articles**:
  - [Battery aging mode identification across NMC compositions and designs using machine learning](https://www.cell.com/joule/fulltext/S2542-4351(22)00525-6)



### 31. Predicting Battery End of Life from Solar Off-Grid System Field Data Using Machine Learning
This dataset contains field data from 1027 lead-acid batteries used in solar off-grid systems across sub-Saharan Africa. The data includes performance metrics for batteries used in lighting, phone charging, and small appliances.
- **Link**: [Download Dataset](https://ora.ox.ac.uk/objects/uuid:e41d3d4c-f74e-4d76-81fd-0caa77ec6cec)
- **Related Articles**:
  - [Predicting battery end of life from solar off-grid system field data using machine learning](https://www.cell.com/joule/fulltext/S2542-4351(21)00532-8)


### 32. ISU-ILCC Battery Aging Dataset
The ISU-ILCC battery aging dataset was collected jointly by the System Reliability and Safety Laboratory at Iowa State University (ISU), now the Reliability Engineering and Informatics Laboratory (REIL) at the University of Connecticut, and Iowa Lakes Community College (ILCC). The dataset is designed to study the dependency of battery capacity fade from three stress factors: charge rate, discharge rate, and depth of discharge. The dataset contains cycle aging data from 251 lithium-ion (Li-ion) polymer cells (also called lithium polymer cells) cycled under 63 unique conditions. The current release contains 238 cells; the other 12 cells have not completed the testing (data from those cells will be included in a future release).
- **Link**: [Download Dataset](https://iastate.figshare.com/articles/dataset/_b_ISU-ILCC_Battery_Aging_Dataset_b_/22582234)
- **Related Articles**:
  - [Predicting battery lifetime under varying usage conditions from early aging data](https://www.cell.com/cell-reports-physical-science/fulltext/S2666-3864(24)00127-9?uuid=uuid%3Ac42a1934-ee17-4e4b-aa93-172b4d2db1d5)

### 33. Dataset: Comprehensive battery aging dataset: capacity and impedance fade measurements of a lithium-ion NMC/C-SiO cell 
The dataset contains over 3 billion data points from 228 commercial NMC/C+SiO lithium-ion cells aged for almost 600 days under a wide range of operating conditions.
- **Link**: [Download Dataset](https://radar.kit.edu/radar/en/dataset/kww7jv8ajuvchcah.Comprehensive%2Bbattery%2Baging%2Bdataset%253A%2Bcapacity%2Bimpedance%2Bfade%2Bmeasurements%2Blithium-ion%2BNMC%252FC-SiO%2Bcel#)
- **Related Articles**:
  - [Comprehensive battery aging dataset: capacity and impedance fade measurements of a lithium-ion NMC/C-SiO cell](https://www.nature.com/articles/s41597-024-03831-x)
  - [Bidirectional Charging Systems and Battery Lifetime Modeling for Vehicle-to-Grid Applications](https://publikationen.bibliothek.kit.edu/1000174456)
 
### 34. Source data: Revealing how internal sensors in a smart battery impact the local graphite lithiation mechanism

- **Link**: [Download Dataset](https://www.nature.com/articles/s41467-024-54656-6#Sec14)
- **Related Articles**:
  - [Revealing how internal sensors in a smart battery impact the local graphite lithiation mechanism](https://www.nature.com/articles/s41467-024-54656-6#Abs1)

### 35. Source data: Generative learning assisted state-of-health estimation for sustainable battery recycling with random retirement conditions
- **Link**: [Download Dataset](https://www.nature.com/articles/s41467-024-54454-0#Sec19)
- **Related Articles**:
  - [Generative learning assisted state-of-health estimation for sustainable battery recycling with random retirement conditions](https://www.nature.com/articles/s41467-024-54454-0#Abs1)


### 36. Source data: Reuse and recycling pathway of retired-batteries
- **Link**: [Download Dataset](https://github.com/RuifeiMa/Reuse-and-recycling-pathway-of-retired-batteries)
- **Related Articles**:
  - [Pathway decisions for reuse and recycling of retired lithium-ion batteries considering economic and environmental functions](https://www.nature.com/articles/s41467-024-52030-0#Abs1)



### 37. Challenges and opportunities in truck electrification unveiled by big operational data

- **Link**: [Download Dataset](https://springernature.figshare.com/articles/dataset/Challenges_and_opportunities_in_truck_electrification_unveiled_by_big_operational_data/24421210?file=44809303)
- **Related Articles**:
  - [Challenges and opportunities in truck electrification revealed by big operational data](https://www.nature.com/articles/s41560-024-01602-x#Abs1)

### 38. Dataset - Dynamic cycling enhances battery lifetime
The study presents a systematic comparison of dynamic discharge profiles, representative of electric vehicle driving, with constant-current discharge profiles, commonly used in laboratory testing. The results indicate that dynamic discharge profiles can extend the lifetime of lithium-ion batteries significantly. Specifically, under identical average current and voltage conditions, dynamic profiles result in up to a 38% increase in equivalent full cycles at the battery's end-of-life. This enhancement is attributed to the influence of low-frequency current pulses and time-induced aging, as revealed through explainable machine learning. These findings emphasize the necessity of incorporating realistic load profiles in the evaluation of new battery chemistries and designs to better understand aging mechanisms and improve battery performance.
- **Link**: [Download Dataset](https://purl.stanford.edu/td676xr4322)
- **Related Articles**:
  - [Dynamic cycling enhances battery lifetime](https://www.nature.com/articles/s41560-024-01675-8#data-availability)


### 39. Stanford Long Term Calendar Aging Dataset
This dataset contains calendar aging from eight different cell types stored at 2 different SOCs and 4 different temperatures. The raw data contains all the voltage and current data at each diagnostic cycle conducted at regular intervals throughout the storage period for the cells. Cell Types: K2 Energy LFP18650E/K2 Energy LFP18650P/Panasonic NCR18650B/Panasonic NCR18650GA/Sony-Murata US18650VTC6/Tenergy 302030/Ultralife 502030/Ultralife UBP001; Storage SOC Conditions: 50%/100%; Storage Temperatures: 24°C/45°C/60°C/85°C; 
- **Link**: [Download Dataset](https://osf.io/ju325/)
- **Related Articles**:
   - [A decade of insights: Delving into calendar aging trends and implications](https://www.cell.com/joule/fulltext/S2542-4351(24)00510-5)


### 40. Battery Capacity Prognostics Dataset for On-Road Electric Vehicles
This dataset provides a comprehensive dataset for analyzing and predicting the capacity degradation of lithium-ion batteries in electric vehicles (EVs). Collected from 20 EVs over approximately 29 months, the dataset includes charging data, labeled capacity values derived from statistical methods, and features optimized through data-driven algorithms. 
- **Link**: [Download Dataset](https://github.com/shiyunliu-battery/battery-charging-data-of-on-road-electric-vehicles)
- **Related Articles**:
   - [Prognostics of battery capacity based on charging data and data-driven methods for on-road vehicles](https://www.sciencedirect.com/science/article/pii/S0306261923003185#ab005)

### 41. WMG-DIB Data
This dataset provides a rich dataset for understanding battery performance degradation. It includes data from 25 cylindrical lithium-ion cells aged through controlled electrical cycling at 25°C to predefined SOH breakpoints (80%, 85%, 90%, 95%, and 100%). The dataset features reference performance tests (RPT), electrochemical impedance spectroscopy (EIS) measurements across various states of charge (SOC) and temperatures, and key metrics derived from EIS plots. 
- **Link**: [Download Dataset](https://data.mendeley.com/datasets/mn9fb7xdx6/3)
- **Related Articles**:
   - [Dataset for rapid state of health estimation of lithium batteries using EIS and machine learning: Training and validation](https://www.sciencedirect.com/science/article/pii/S2352340923002767)
 
### 42. WMG Calendar Ageing Dataset - LGM50 Commercial Cells (39 Storage Conditions)
The dataset presents comprehensive calendar aging data collected from commercial LGM50 lithium-ion cells under controlled storage conditions: Storage Temperatures: 0°C, 25°C, and 45°C; State of Charge (SOC): 13 distinct levels per temperature condition; Test Duration: Two-years per condition (on average).
The dataset consists of MATLAB (.mat) files containing cell cycling results from Reference Performance Tests (RPTs) conducted throughout the aging study.

- **Link**: [Download Dataset](https://zenodo.org/records/14577286)
- **Related Articles**:
   - [Lithium-Ion Battery Degradation Modelling Using Universal Differential Equations: Development of a Cost-Effective Parameterisation Methodology](https://www.sciencedirect.com/science/article/pii/S0306261924026059#sec1)
 
### 43. Cycle aging data of automotive-grade lithium ion battery cells under realistic and accelerated load conditions
This data set contains cycle aging data from three automotive-grade NMC|Gr pouch cells (used in the VW ID.3) subjected to three different usage patterns over a duration of 3+ years. Please refer to the linked article for cell and measurement specifications. All measurements are provided as .txt files (raw files exported from the battery test system).

- **Link**: [Download Dataset](https://mediatum.ub.tum.de/1748915)
- **Related Articles**:
   - [Understanding lithium-ion battery degradation in vehicle applications: Insights from realistic and accelerated aging tests using Volkswagen ID.3 pouch cells](https://www.sciencedirect.com/science/article/pii/S2352152X25000702#d1e2292)

### 44. Retired lithium-ion batteries dataset
- **Link**: [Download Dataset](https://zenodo.org/records/14562266)
- **Related Articles**:
   - [Capacity estimation of retired lithium-ion batteries using random charging segments from massive real-world data](https://www.sciencedirect.com/science/article/pii/S2666386425000438?dgcid=rss_sd_all#abs0020)

### 45. Synthetic Duty Cycles from Real-World Autonomous Electric Vehicle Driving: Accompanying Data
- **Link**: [Download Dataset](https://purl.stanford.edu/ky011nj6376)
- **Related Articles**:
   - [Synthetic duty cycles from real-world autonomous electric vehicle driving](https://www.sciencedirect.com/science/article/pii/S2666386423003314)

### 46. Model-Constrained Deep Learning for Online Fault Diagnosis in Li-ion Batteries over Stochastic Conditions
The authors utilize data uploaded from vehicle onboard Battery Management Systems (BMS) for network design. They have released a real-world vehicle dataset containing 18.2 million valid entries collected from 515 vehicles, which was gathered by the BMS data center on the cloud.
The dataset primarily consists of data from three battery manufacturers, which, due to confidentiality restrictions, are referred to as DTI, QAS, and GIS in the paper. In addition to normal operating data, the dataset also includes four types of rare and critical safety failure samples: Thermal runaway, Electrolyte leakage, Internal short circuit, Excessive ageing.

- **Link**: [Download Dataset](https://zenodo.org/records/10656500)
- **Related Articles**:
   - [Model-constrained deep learning for online  fault diagnosis in Li-ion batteries over stochastic conditions](https://www.nature.com/articles/s41467-025-56832-8)

### 47. Data from: "Lithium-ion battery degradation: comprehensive cycle ageing data and analysis for commercial 21700 cells"
These data were generated from battery cell ageing experiments that included break-in cycles and Reference Performance Tests (RPTs), alternating with performance checks and ageing cycles. Each cell was base-cooled at set temperatures using bespoke rigs, with full experimental details available in linked publications. The repository is structured according to each “Experiment,” containing folders for “Summary Data,” “Processed Timeseries Data,” and “Raw Data.” The “Summary Data” folder holds metrics such as capacity, resistance, degradation mode analysis, and ageing statistics. “Processed Timeseries Data” includes subtest-specific voltage, current, and temperature in .csv files, while “Raw Data” comprises proprietary .mpr and .mpt files. An “experimental_metadata” .xlsx and a Jupyter notebook are provided for straightforward data parsing, analysis, and visualization. 

- **Link**: [Download Dataset](https://zenodo.org/records/10637534)
- **Related Articles**:
   - [Lithium-ion battery degradation: Comprehensive cycle ageing data and analysis for commercial 21700 cells](https://www.sciencedirect.com/science/article/pii/S0378775324001368#abs0015)
   - [The importance of degradation mode analysis in parameterising lifetime prediction models of lithium-ion battery degradation](https://www.nature.com/articles/s41467-025-57968-3#Abs1)

 ### 48. Air-cooled lithium-ion battery pack (LIBP) extracted from a plug-in hybrid vehicle (PHEV)
- **Link**: [Download Dataset](https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/THZTJC)
- **Related Articles**:
  - [Thermal fault detection of lithium-ion battery packs through an integrated physics and deep neural network based model](https://www.nature.com/articles/s44172-025-00409-2#Abs1)
 
 ### 49. Long-Term Sweat Testing Data for Second-Life Batteries
This dataset contains long-term cycling data from repurposed lithium-ion batteries originally used in electric vehicles and redeployed in second-life stationary energy storage applications. It includes data from six distinct use cases that simulate real-world scenarios such as time-of-use tariffs, PV-self consumption, and frequency response services. The raw data was recorded using a Chroma 17020 battery cycler and testing began in 2019. The testing is currently still on going and the repository will be periodically updated. Files were initially stored as large continuous logs and have been processed into individual charge-discharge cycles (in .csv format) for ease of use. The dataset supports research in battery ageing, second-life performance assessment, and state of health modelling.
- **Link**: [Download Dataset](https://repository.lboro.ac.uk/articles/online_resource/Long-Term_Sweat_Testing_Data_for_Second-Life_Batteries/28732490/2)
- **Related Articles**:
  - [Long-Term Sweat Testing Dataset for Second-Life Batteries](https://www.nature.com/articles/s41597-025-05360-7#Abs1)
 
 ### 50. Aging dataset LCO battery with mechanical measurements

Aging dataset of a commercial 22Ah LCO-graphite pouch Li-Po battery.
The cycling procedure involves aging steps consisting of 22 aging cycles at 1C CC discharge and C/2 CC-CV charge, with no pauses in between. Periodic RPTs are carried out after each aging step. In particular, two series of RPTs are alternated, referred to as RPT-A and RPT-B, with this pattern: 22 aging cycles -> RPT-A -> 22 aging cycles -> RPT-A + RPT-B -> repeat.
The RPT-A consists of three high rate cycles (1C CC discharge and C/2 CC-CV charge) with 1 hour rest.
The RPT-B consists of three high rate cycles (1C CC discharge and C/2 CC-CV charge) with 1 hour rest, one low rate cycle (C/20) and the HPPC test. In this way, high rate test cycles are carried out periodically every 25 cycles (22 aging + 3 test), whereas low rate test cycles and HPPC are carried out every 50 cycles. The exact number at which each reference performance test was carried out is reported in the sixth column of the data structure.

In total, 1125 cycles were achieved untill SOH 70%.

The cycling reference performance tests (high rate cycling 1C-C/2, and low rate cycling C/20-C/20) are reported in the MATLAB structure called Aging_Dataset_Cycling. On the other, the data of the HPPC tests are reported in the MATLAB structure called Aging_Dataset_HPPC.

The data structure of cycling reference performance tests is a MATLAB cell organized so that in the first row there are data of RPT-A (high rate cycles), and in the second row the data of RPT-B (low rate cycles). In the first column there are discharge data, in the second column the charge data, in the third column the data recorded in the one hour rest after discharge and in the fourth column the data recorded in the one hour rest after charge. In each element of this 2x4 matrix there is a cell containing the structures referring to each reference performance tests. The different reference performance tests are organized so that in the row there are the reference performance tests carried out at different aging cycles (detailed in the vector in the sixth column of the main data structure) and in the column there are the tests repeated at the same aging cycles for statistical studies. Generally RPT-A tests are repeated three times and RPT-B tests are repeated one times. Then, each cell, e.g. D{1,1}{1,1} contains a structure with the data of that test coded as explained in the bullet list below.

- **Link**: [Download Dataset](https://zenodo.org/records/14914172)
- **Related Articles**:
  - [Aging diagnostics in lithium-ion batteries with differential mechanical measurements](https://www.sciencedirect.com/science/article/pii/S0306261925002545#da1)


 ### 51. Dataset of lithium-ion battery degradation based on a forklift mission profile for state-of-health estimation and lifetime prediction

 - **Link**: [Download Dataset](https://www.sciencedirect.com/science/article/pii/S2352340923009228#abs0001)
- **Related Articles**:
  - [Dataset of lithium-ion battery degradation based on a forklift mission profile for state-of-health estimation and lifetime prediction](https://www.sciencedirect.com/science/article/pii/S2352340923009228#abs0001)
  - [Sensitivity analysis for reliable state-of-health estimation based on battery partial charging](https://www.sciencedirect.com/science/article/pii/S2666386425002450?dgcid=rss_sd_all#appsec2)

 ### 52. A dataset of over one thousand computed tomography scans of battery cells
 
1015 commercially available batteries were scanned using a X-ray computed tomography system. These scans were processed into a set of images that capture the major axes of the battery. For cylindrical cells, these are radial and axial views of the battery. For pouch and prismatic cells, these are x-y, x-z, and y-z views of the battery.
 - **Link**: [Download Dataset](https://plus.figshare.com/articles/dataset/A_dataset_of_over_one_thousand_computed_tomography_scans_of_battery_cells/25330501)
- **Related Articles**:
  - [A dataset of over one thousand computed tomography scans of battery cells](https://www.sciencedirect.com/science/article/pii/S235234092400581X?via%3Dihub)
---

Links to external sites

- [Battery Archive](https://batteryarchive.org/)
- [Data Dryad](https://datadryad.org/stash)
- [Zenodo](https://zenodo.org/)
- [Mendeley](https://data.mendeley.com/)
- [Iontech.Cloud](https://iontech.cloud/)
- [USABC](https://uscar.org/usabc/)
- [US.Data.GOV](https://data.gov/)
- [EPA](https://www.epa.gov/vehicle-and-fuel-emissions-testing/dynamometer-drive-schedules)
- [Sandia.gov](https://www.sandia.gov/ess/tools-resources/rd-data-repository)


