## ViVA: Verification and Validation Assessment, a Capella Viewpoint
This a Capella Viewpoint for **V&V activities** developed with Capella Studio. 

![ViVA Icon](ViVA_icon.png)

### ViVA Viewpoint Overview

The **ViVA** Viewpoint has been developed to streamline the creation and management of requirements within Capella.
It enables users to generate requirements with standardised and structured information, ensuring the homogenisation and consistency of data across the entire model.

### Key Features

* Standardised Requirement Creation
	The viewpoint introduces predefined attributes and templates for requirements, improving consistency and reducing ambiguity.
	This standardisation is crucial when managing hundreds or even thousands of requirements in large-scale projects.

* Faster Requirement Authoring
	The process of creating and maintaining requirements has been made simpler and more efficient, significantly reducing the time needed for documentation.

* Dynamic Visualisations
	The viewpoint includes dynamic diagrams that automatically change colour based on specific attributes within the model.
	This feature helps users quickly identify potential issues or inconsistencies and resolve them more effectively.

### Integration with Python4Capella Scripts

The viewpoint is complemented by two Python scripts designed to run in Python4Capella.
These scripts enable the automatic extraction of key information into Excel matrices:

* Verification Matrix
Extracts all requirements from the selected diagram, including their key attributes.
The output groups requirements by category, providing a clear and traceable overview.

* Validation Matrix
Traverses the entire model to collect information across all abstraction levels.
This allows users to trace requirements back from system implementation to stakeholder needs, ensuring that the operational-level objectives are fully satisfied.

### Tutorial and Documentation

Finally, a step-by-step tutorial is provided to guide users through the creation of this viewpoint.
Given the limited availability of resources and documentation on Capella Studio, this tutorial was considered essential to share the knowledge and experience gained during the development process.
The goal is to support and inspire future open-source viewpoint developments within the Capella community.


## Getting Started

This projects has the source code of the viewpoint and the packaged viewpoint (For direct use).

### Prerequisites
To change in the source code you will need to have:
* [Capella Studio](https://www.eclipse.org/capella/download.html) v.7.0.1 - Open source SDK to develop Capella add-ons

To use the packaged version of the project you will need to have:
* [Capella](https://www.eclipse.org/capella/download.html) v.7.0 - Open source MBSE tool to create system, software or hardware architectures


### Installing the source code
  Before starting you should make sure that Capella Studio is well installed (mentioned above)

  **Step 1: Download the project**

  Clone the project to your local repository

  **Step 2: Opening the project**

  Use Capella Studio to open and edit the project

### Generating the viewpoint
  This step is to generate the viewpoint after editing the source code

  **Generate**
  
  Right click in the .spec.vptext and click on Generate Viewpoint

  **Generate and package**
  
  Right click in the .spec.vptext and click on Generate and Package Viewpoint

### Adding Viewpoint to Capella
 This step is to integrate the developed Viewpoint into Capella 
  
  **Step 1 : Add the viewpoint to Capella**
  
  Copy the generated package (Extracted) into the repository of capella/eclipse/dropins 

  **Step 2 : Open viewpoint**
  
  Windows -> Show View -> Others
  
  Choose Viewpoint Manager under Kitalpha
  
  **Step 3 : Reference the viewpoint**
  
  Right click on the viewpoint and press Reference
  
  **Step 4 : Layers**
  
  In the layers button, press on the viewpoint in order to view the viewpoint tools in the palette
	
  **Step 5 : Use the viewpoint**
  

## Built With

* [Capella Studio](https://www.eclipse.org/capella/download.html) v.7.0- Download page


## Authors
* **Chiara My** 

