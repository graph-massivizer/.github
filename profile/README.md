# Graph-Massivizer

Graph-Massivizer researches and develops a high-performance, scalable, and sustainable platform for information processing and reasoning based on the massive graph representation of extreme data. It delivers a toolkit of five open-source software tools and FAIR graph datasets covering the sustainable lifecycle of processing extreme data as massive graphs. The tools focus on holistic usability (from extreme data ingestion and massive graph creation), automated intelligence (through analytics and reasoning), performance modelling, and environmental sustainability tradeoffs, supported by credible data-driven evidence across the computing continuum. The automated operation based on the emerging serverless computing paradigm supports experienced and novice stakeholders from a broad group of large and small organisations to capitalise on extreme data through massive graph programming and processing.

## [Graph-Massivizer Toolkit](https://github.com/graph-massivizer/graph-massivizer-toolkit)
The Graph-Massivizer Toolkit is an integrated platform that leverages the unique researched functionalities in each separate Graph-Massivizer tool. In the integrated toolkit, algorithms that perform basic graph operations (BGO) developed by Graph-Inceptor and Graph-Scrutinizer as well as other open source libraries are integrated so that they can be executed efficiently and in a green-aware fashion within diverse hardware environments according to the advanced techniques developed by Graph-Optimizer, Graph-Greenifier, and Graph-Choreographer.

## Tools

### [Graph-Inceptor](https://github.com/graph-massivizer/graph-inceptor)
The Graph-Inceptor tool is comprised of two distinct tools serving different use cases for ingesting and processing massive graphs.

- [GraphMa](https://github.com/graph-massivizer/graph-inceptor-graphma)
GraphMa, a component of the Graph-Inceptor tool, integrates principles of pipeline computation using modular, composable functions to provide structured graph data analysis and processing using computational abstractions such as computation as type, higher-order traversal abstraction, and directed data-transfer protocol.

- [ETL Pipeline](https://github.com/graph-massivizer/graph-inceptor-etl-pipeline)
The Graph-Inceptor ETL Pipeline creates KGs and stores them in batches from large data sources using semantic mappings deployed on a scalable IT cloud infrastructure consisting of servers and storage systems.

### [Graph-Scrutinizer](https://github.com/graph-massivizer/graph-scrutinizer)
Graph-Scrutinizer provides various BGO analytics, such as sampling, summarisation, traversal, or ML (e.g., GNN) algorithms, translated into optimised implementations for heterogeneous hardware (HPC, edge, cloud). Examples of the Graph-Scrutinizer algorithms that can be used in BGOs include [TS2G2](https://github.com/graph-massivizer/ts2g2) and [Go Network](https://github.com/graph-massivizer/go-network).

### [Graph-Optimizer](https://github.com/graph-massivizer/graph-optimizer)
Graph-Optimizer combines analytical models, micro-benchmarking, graph sampling, simulation, and automated validation, to predict the performance and energy footprint of a given graph processing workload.

### [Graph-Greenifier](https://github.com/graph-massivizer/graph-greenifier)
Graph-Greenifier is a simulation tool for data centre operators and application developers to create scenarios that quantify the carbon impact of workloads on different locations and hardware, making informed decisions.

### [Graph-Choreographer](https://github.com/graph-massivizer/graph-choreographer)
Graph-Choreographer is a serverless orchestration tool for executing single, ensemble and batch graph applications on the computing continuum, scheduled using performance and energy tradeoffs.

## Use Cases

### Green and Sustainable Finance
Synthetic financial data generation of extreme volumes of stocks and future commodities, adaptable to additional financial securities such as options, bonds, exchange-traded funds, mutual funds, and currencies

### Global Foresight for Environment Protection
Analysis of company-related events from past data, patterns identification in a common sequence, and prediction of the most likely following events by matching them

### Green AI for Sustainable Automotive Industry
Integration of traditional expert knowledge with sensor data for quality monitoring in manufacturing, combining KGs with time-series sensor data models to enhance explainability, accuracy, and flexibility in quality predictions, and provisioning of expert insights and real-time measurements for superior quality control

### Data Centre Digital Twin for Sustainable Exascale Computing
Continuous prediction of compute node failures in a high-performance computing system based on an anomaly prediction model that leverages the nodes’ physical layout integrated into the monitoring system with a continuous graph neural network deployment pipeline
