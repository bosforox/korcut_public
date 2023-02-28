# Korcut

## Motivation
Robots are widely used complex mechatronic systems. They are built as a combination of complex electronic and mechanical subsystems and multi-layered software structures. As systems developed across disciplines, mastering such a whole is highly complex, even for developers or researchers. Although standardization and simplification through modularity help to overcome development challenges, it is still far from easy to understand and develop for non-expert users who lack prior knowledge and experience. We hypothesize that semantic representation of knowledge in this domain can help bridge this gap.


## Covered domains by Korcut family:
* Fundamentals
* Robot hardware
  * Robot mechanics
    * Material types
    * Robot subsystems
  * Robot electronics
    * Sensors
    * Communication
* Environment
* Requirement analysis
* Evaluation criterion

# Ontology development method of Korcut

To develop an ontology, it is important to know details about the domains covered, with an emphasis on use cases as well as the necessary information about elements and properties. Expert support is required to determine the right workspace and parameterize the elements to set the right formal description. Defined development development methodologies developed by [Noy & McGuinness (Ontology development 101)](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf) and [(De Nicola, Missikoff and Navigli (A soft engineering approach ontology building)](http://wwwusers.di.uniroma1.it/~navigli/pubs/De_Nicola_Missikoff_Navigli_2009.pdf) were followed to support the design and implementation steps of the ontology.


## Survey to determine the domain and scope of a robot ontology

To develop an ontology, it is important to know details about the domains covered, with an emphasis on necessary-sufficient information about elements (objects such as classes and individuals) and properties as well as use cases. The support of experts is necessary to parameterize the elements in order to identify the right workspace and set the right formal description. For this purpose, an initial survey was conducted and the results analyzed. The analysis of the results is available on Zenodo [![Survey1 on Zenodo](https://zenodo.org/badge/DOI/10.5281/zenodo.4646974.svg)](https://doi.org/10.5281/zenodo.4646974). Subsequently, a second survey was carried out to measure the usefulness of the obtained ontology and other tools. The results of the second survey are also available on Zenodo [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7585182.svg)](https://doi.org/10.5281/zenodo.7585182).


## Story board
In the development were considered two following scenarios, which were more chosen by volunteers in the performed survey.
* Scenario 8 is the recommended most frequent story board (30,34% of volunteers).
  *  A third party company chief engineer Ms. Purple is responsible for the complex system design with off-the-shelf products (of ACME and others) and development of the required control software. She knows some of standard market products with generic information (e.g. laser scanner, max. range, Ethernet port, IP54). In order to strengthen her customer portfolio, she wants to gain new solution options that can be artificially generated and are not easy to find out as solution ideas by an expert person due to the complexity or lack of knowledge in various domains. Therefore, she requests to ACME to get a solver with a suitable knowledge base with well semantically described components that can fulfil this task

* Scenario 7 is the recommended most frequent story board regarding  the perspective of domains responses (22,47% of volunteers).
  * Prof. Harris is working on the development of new robots at ACME to support ill or disabled people to compensate their inabilities through robots. He wants to know the general skills of a system with respect to subsystem capabilities (like sensor functions)

## Competency questions:
The following competency questions were considered in the development of the korcut according to the survey results.
* How long is the operating time of a particular robot under certain conditions?
* Which robot properties should I consider when selecting a robot?
* Which grippers are suitable for underwater and Sherpa TT robot?
* Which characteristics of a robot affect its suitability for electromagnetic compatibility?
* What is the best payload choice for a maximum weight of 500g?

## Terminology
With respect to the survey results, the example vocabulary is as follows.

### Vocabulary:

* Environment (general)
  * indoor
  * space
  * underwater
* Robot parts (general)
  * gripper
  * manipulator
  * sensor head
* Software drivers
  * ROS driver
  * ROCK driver
  * Linux driver
* Sensor(special)
  * sensor resolution
  * measurement range
  * tolerance
* Sensor (general)
  * Radar
  * Lidar
  * U-sonic
* Data comm. Interface (gen.)
  * USB 3.0
  * ethernet
  * serial bus
* Robot locomotion organ
  * wheel
  * leg
  * arm
* Materials (general)
  * copper
  * aluminium
  * plastic
* Motor parts (special)
  * BLDC Motor type MY10
  * gearbox type ZKY12
  * housing type ES81
* Connector interface
  * RJ-45
  * Sub-D
  * USB 1.0


## Topical Map:
* coming soon...


## Contacts:
* Mehmed Yüksel <mehmed.yueksel@dfki.de>

## Copyrights
All rights reserved.

Copyright &copy; 2021, Mehmed Yüksel DFKI GmbH / Robotics Innovation Center
