---
title: Automating Workloads with ARM Templates
subtitle: Project for CalTech Az303 Course
author: David Hill, Jr. 
papersize:
- a4
fontsize:
- 12pt
geometry:
- margin=1in
fontfamily:
- charter
header-includes:
- \setlength\parindent{24pt}
- \usepackage{placeins}
- \usepackage{graphicx}
- \graphicspath{ {./images/} }
---

\maketitle
\pagenumbering{arabic}
\setcounter{page}{1}

## Description

The Rand Enterprises Corporation wants to test the ARM template to bring infrastructure as code into practice. They have decided to work on project RandEnt to verify the functionality.

The operations team at Rand decides to define entire networking architecture using the ARM template, once that’s in place they intended to create the storage account along with virtual machine housing their application. 

As Rand Enterprises works extensively on delivering Image-based content for their global audience in a secure way by avoiding the Azure Storage account access to the public internet. The communication from the application in the VM to the Azure Storage account must take place via the internal network of Azure.

The expectation of the operation team is to Rather than deploying resources in Azure independently, they should leverage Azure ARM templates to deploy and provision all resources in templatize format.

### Following requirements should be met: 
- [X] Define the Network
- [X] Extend the network with Compute and Storage
- [X] Create the Storage account container for Images & configure service endpoints


## Define the Network

The first part of this project was defining the network which I did by using the azure code snippets and modifying the values. 



## Extend the network with Compute and Storage



## Create the Storage account container for Images & configure service endpoints


