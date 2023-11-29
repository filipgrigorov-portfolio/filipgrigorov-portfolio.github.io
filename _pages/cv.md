---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* DEC Pure and Applied Science (physics and mathematics) (Dean's Honours List), Dawson College, 2004-2006
* BCom Finance, McGill University, 2006-2009
* BEng Mechanical Engineering (Dean's Honours List), McGill University, 2010-2013
* MSc in Computer Science, University of Toronto, 2023-present

Honours and Awards
======
* Engineering Class of 1953 Scolarship, 2011
* Ram & Durga Panda Scholarship, 2012

Work experience
======
* Vector Institute: Faculty Affiliate Researcher, 2023

* Torc Robotics: Staff Computer Vision Engineer, 2023-present

* Algolux: Senior Computer Vision/Deep Learning Research Engineer, 2021-2023 (**Acquired by Torc Robotics**)
  * Owning research and development of our multi-object 2D/3D tracker
  * Owning research and development of our stereo, geometric and 3D post-processing
  * Developing stereo-based dense depth estimation
  * Leading, researching and developing an embedded object detection model with post-processing (CPU optimized implementation) and an ISP stack (CPU optimized/quantized implementation) on an automotive SoC
  * Developing tensorrt-based deep learning models (object detection, active learning, road segmentation, entropy etc.), pre-processing and post-processing on NVIDIA
  * Playing a major role in the architectural and algorithmic design of our production perception stack for self-driving cars
  * Converting deep learning models

* Alcatraz AI: Senior Computer Vision/Machine Learning Research Engineer
  * Designed a multi-face tracking algorithm
  * Designed a tailgate detection module using the above-mentioned algorithm
  * Designed a new spoof detection module under pytorch, from scratch
  * Created several spoof detection architectures, from scratch
  * Designed the auto-annotation infrastructure for the spoof feature and generalized to other algorithms
  * Optimized the spoof detection algorithm under Nvidia's tensorRT CUDA-based framework
  * Integrated the algorithm into our C++ code-base. The code is highly optimized for performing well on an edge device
  * Working continuously, on the improvement of the algorithm in python and the surrounding computer vision heuristics within the C++ code-base such as head-pose estimation, depth quality and many other metrics
  * Worked on the spatial transformations algorithms relating to the geometry of our device
  * Working on the continuous improvement and maintenance of our C++ logic code-base on the device. This includes classic computer vision algorithms, image processing and business logic support as well as integration tests. This also includes communication to and from our peripheral hardware such as LED and OLED
  * Improving and maintaining the code-base for our stereo (RGB, IR and depth) sensors
  * Initiated our data collection effort, from scratch
  * Designed and created a python-based data collection pipeline, from scratch, relating to the spoof detection effort. This pipeline is backed up by AWS' s3
  * Supervised 2 interns working on "Bad light detection" and "Head pose estimation using 5 data points"

* Gameloft: Computer Vision/Machine Learning Research Engineer, 2016-2018
  * Worked as part of the Research and Development team in Montreal, Canada, designing and implementing intelligent systems on a robotic platform, using various machine learning and artificial intelligence techniques, and tools to quality assurance automation regarding mobile gaming
  * Worked on object and blob detection algorithms under tensorflow and keras
  * Worked on optical character recognition (OCR) algorithms using tesseract and classical methods
  * Initiated and designed our first reinforcement-learning prototype, based on the A2C algorithm, to automate playing and testing a mobile game racing simulator
  * Worked on many of the lua scripting for auto-testing pre-determined rules
  * Worked on the C++ logic communicating with the robotics system, screen capture system and the dashboard on the server
  * Worked on the pre-processing and data engineering in regards to our ML-based models
  * Worked on many image processing techniques in the pipeline in regards to the captures from the device

* Gameloft: Computer Vision/Intelligent Systems Research Engineer, 2016
  * Worked as part of the Research and Development team in Montreal , Canada, designing and implementing intelligent systems on a robotic platform, using various computer vision and artificial intelligence techniques, and tools to quality assurance automation regarding mobile gaming
  * Worked on our UI/UX using Qt
  * Worked on our lua to C++ compilation process using the lua compiler for auto-generating rules to test
  * Worked on the first-generation classical computer vision-based architecture to develop tools for auto-testing games
  * Worked on the communication with the hardware and the code-base
  * Worked on our image processing and object detection algorithms using classical methods (blob detection, color segmentation etc.)
  * Worked on the logic behind loading up the pre-written lua scripts for the automated AI system
  * Participated in the design of the second-generation ML-based architecture to develop tools for auto-testing games, from scratch
  * Participated in the migration of our C++ code-base from the first to the second generation intelligent system
  * Worked on our python to C++ binding
  * Worked on our first detection pipelines under keras and tensorflow for the second-generation architecture

* Maya HTT: Software Engineer for Computer Aided Engineering (CAE) Products, 2014-2016
  * Worked on developing and customizing Maya's CAE (Computer-Aided Engineering) products
  * Worked on customizing solutions to automate customer’s workflows in using Maya's thermal, fluid, laminate and durability simulation products
  * Worked within NX CAE, sold by Siemens PLM Software (such as 3D geometry simulation and meshing features)
  * Applied NX Open API for customized applications in C++

* Bianor: Software Engineer, 2014
  * Worked on iOS 7 (Cocoa Touch framework, Core Foundation, Quartz, Core Plot and UIKit frameworks) application development in Objective-C, participating in the conceptual design, relational design, client requirements, programming design and implementation of the application
  * Worked with web content consumption such as RESTful and JSON
  * Worked with subversion and continuous integration

* McGill University Health Centre: Engineering Research Intern (McGill University, Harvard Medical School and MIT), 2013
  * Worked as a parallel high-resolution MRI RF coils engineering intern, with academic collaborators/supervisors from Harvard Medical School and Health Science and Technology, MIT at the Massachusetts General Hospital, Boston, USA, and Siemens Healthcare
  * Designed, under my supervisor's attention, the patient helmet cage (3D-printed)
  * Designed, under my supervisor's attention, and built the MRI radio-frequency circuitry
  * Designed, under my supervisor's attention, and build the pre-amp electronics necessary to control the radio signal from the coils to the MRI
  * Performed various tests to eliminate any noise and interference between the coils and to increase the signal-to-noise ratio
  * Participated in the publication of this research work, entitled "Dense, Shape-Optimized Posterior 32-Channel Coil for Sub-Millimeter Functional Imaging of Visual Cortex at 3-Tesla"
  
Skills
======
* C/C++/CUDA
* python
* Deep learning/Machine learning
* Computer vision
* 3D computer vision
* Image processing
* Reinforcement learning
* Statistical learning
* SLAM
* Simulation
* Deep learning frameworks
  * pytorch
  * tensorflow
  * keras
  * tensorrt
  * dlib
  * opencv
* git
* data
  * engineering
  * augmentation
  * aws/boto3

Publications
======
  Reza Farivar, Filip Grigorov, Andre J. van der Kouwe, Lawrence L. Wald,
  Boris Keil (2015, July 27). Dense, shape-optimized posterior 32-channel
  coil for submillimeter functional imaging of visual cortex at 3T. Magnetic
  Resonance in Medicine. Retrieved from
  https://doi.org/10.1002/mrm.25815

Patents
======
SYSTEM AND METHOD FOR CONTROLLING ACCESS TO A BUILDING WITH FACIAL RECOGNITION
US US20190213816 · Issued Nov 7, 2019
