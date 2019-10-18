---
title: "SODA: Software for Organizing Data Automatically"
keywords: organizing, submitting, dataset
sidebar: sparc_sidebar
permalink: soda.html
summary: This page presents the software currently under development for assisting SPARC investigators during data organization and submission 
folder: general
---


## Overview

SODA is a software intended to simplify the organization and submission process of SPARC datasets by handling complex and/or repetitive tasks through an intuitive and interactive interface. It helps users to organize, generate metadata, validate, and submit datasets according to the SPARC Data Standards. SODA will be distributed as a desktop application for Windows, MAC OS, and Linux. The idea for SODA emanated during the December 2018 SPARC Hackathon. It is currently under development and will be released progressively as the features are incorporated. In October 2019, SODA will be able to assist the users in organizing their files/folders automatically, generating their metadata conveniently, and submitting their datasets to Blackfynn. In December 2019, users will be able to push and organize files/folders of a dataset directly on Blackfynn through SODA, thus avoiding the need to create duplicate files locally. In February 2020, it will be possible to validate datasets using the validator developed by the Curation Team. In April 2020, users will be able to manipulate and annotate datasets on Blackfynn. In May 2020, SODA will permit to rapidly convert the file format into a SPARC-defined standard format.

{% include image.html file="SODA-Graphical.png" %}

## SODA main interface

SODA main interface includs a side menu which allows to navigate between the two main features of SODA, "Prepare Dataset" and "Manage and Submit Datasets", as well as access to the "Help" section. The design of the GUI is based on the Electron demo code, whichis freely available.

{% include image.html file="main_interface.png" %}

## Prepare Dataset

This user interface will walk you step by step through the data preparation process. 
1. Organize
2. Convert file format
3. Generate metadata
4. Validate
5. Generate dataset

The first four options permit the selection of desired actions on the dataset which can then be applied under "Generate dataset".

## Manage and Submit Datasets

This user interface will assist you in managing and submitting your datasets on Blackfynn. It will also guide you for annotating your datasets using Blackfynn’s model properties. 
1. Login to your Blackfynn acount
2. Visualize existing dataset 
3. Create new dataset folder
4. Submit new dataset
5. Share a dataset with the curation team
6. Annotate dataset

{% include image.html file="manage_submmit.png" %}

## Help

The help section contains links to various resources for assistance with SODA, the preparation process, Blackfynn, and other.

{% include image.html file="help.png" %}


For more information please contact [Bhavesh Patel](mailto:bpatel@calmi2.org).