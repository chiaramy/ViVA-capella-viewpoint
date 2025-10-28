## ViVA: Verification and Validation Assessment, a Capella Viewpoint
This a Capella Viewpoint for **V&V activities** developed with Capella Studio. 

### ViVA Viewpoint Overview

The ViVA Viewpoint has been developed to streamline the creation and management of requirements within Capella.
It enables users to generate requirements with standardised and structured information, ensuring the homogenisation and consistency of data across the entire model.

### Key Features

*Standardised Requirement Creation
The viewpoint introduces predefined attributes and templates for requirements, improving consistency and reducing ambiguity.
This standardisation is crucial when managing hundreds or even thousands of requirements in large-scale projects.

*Faster Requirement Authoring
The process of creating and maintaining requirements has been made simpler and more efficient, significantly reducing the time needed for documentation.

*Dynamic Visualisations
The viewpoint includes dynamic diagrams that automatically change colour based on specific attributes within the model.
This feature helps users quickly identify potential issues or inconsistencies and resolve them more effectively.

### Integration with Python4Capella Scripts

The viewpoint is complemented by two Python scripts designed to run in Python4Capella.
These scripts enable the automatic extraction of key information into Excel matrices:

*Verification Matrix
Extracts all requirements from the selected diagram, including their key attributes.
The output groups requirements by category, providing a clear and traceable overview.

*Validation Matrix
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
* [Capella Studio](https://www.eclipse.org/capella/download.html) - Open source SDK to develop Capella add-ons

To use the packaged version of the project (QualityAssessment_201912031504.zip) you will need to have:
* [Capella](https://www.eclipse.org/capella/download.html) - Open source MBSE tool to create system, software or hardware architectures


### Installing the source code
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Before starting you should make sure that Capella Studio is well installed (mentioned above)

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 1: Download the project**

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Clone the project to your local repository

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 2: Opening the project**

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Use Capella Studio to open and edit the project

### Generating the viewpoint
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This step is to generate the viewpoint after editing the source code

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Generate**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click in the .spec.vptext and click on Generate Viewpoint

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Generate and package**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click in the .spec.vptext and click on Generate and Package Viewpoint

### Adding Viewpoint to Capella
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This step is to integrate the developed Viewpoint into Capella 
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 1 : Add the viewpoint to Capella**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Copy the generated package (Extracted) into the repository of capella/eclipse/dropins 

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 2 : Open viewpoint**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Windows -> Show View -> Others
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Choose Viewpoint Manager under Kitalpha
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 3 : Reference the viewpoint**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click on the viewpoint and press Reference
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 4 : Layers**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In the layers button, press on the viewpoint in order to view the viewpoint tools in the palette
	
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 5 : Use the viewpoint**
  

## Built With

* [Capella Studio](https://www.eclipse.org/capella/download.html) - Download page


## Authors
* **Chiara My** 


## References
[Creation of viewpoint with Capella Studio 1.1](https://www.youtube.com/watch?v=zvIzyDxAj1c&t=301s) - Youtube tutorial

[Viewpoint: the making of. Customizing Capella with Capella Studio in 20 minutes](https://www.youtube.com/watch?v=lhNvmjHRa0o) - Youtube tutorial

[Viewpoint Creation for Capella with Capella Studio](https://www.youtube.com/watch?v=NWCyKsPfc2Y&t=232s) - Youtube tutorial
