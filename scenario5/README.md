# ASEANZK Cloud Pak for Data – Practicum Scenario 5

## IBM CP4D Installation & Configuration In Openshift

### Overview
IBM Cloud Pak for Data is a unified data and AI platform that connects the right data, at the right time, to the right people anywhere. Running on the Red Hat OpenShift platform simplifies data access, automates data discovery and curation, and safeguards sensitive information by automating policy enforcement for all users in your organization. Make better data-driven decisions and lay the foundation for AI with a data fabric that connects siloed data on-premises or across multiple clouds without data movement. Discover actionable insights and apply trusted data to build, run, automate and manage AI models.
 
This document provides step-by-step instructions to install IBM Cloud Pak for Data on the Red Hat OpenShift cluster. However, before we begin the installation, let’s ensure the following assumptions and pre-requisite are met.

Note: IBM® Cloud Pak for Data images are accessible from the IBM Entitled Registry. In most situations, it is strongly recommended that you mirror the necessary software images from the IBM Entitled Registry to a private container registry. Because we are deploying for demo purposes in this example, I have skipped mirroring IBM Cloud Pak for Data images in the private container registry.

#### Assumptions
•	Installing fresh Cloud pak for data Control Plane, Foundational Services and Operators
•	Red Hat OpenShift cluster has access to a high-speed internet connection and can pull images directly from IBM Entitled Registry.
•	Installing for demo purposes and so, the latest version of the software will automatically install on the Red Hat OpenShift cluster.
•	User has knowledge and experience managing Red Hat OpenShift cluster

#### Pre-Requisite
•	Red Hat OpenShift cluster version 4.6 or later with min 48 vCPU and 192 GB RAM
•	Bastion host with 2 vCPU and 4GB RAM with Linux OS
•	Internet access for Bastion host and Red Hat OpenShift cluster
•	OpenShift Container Storage (OCS) attached to Red Hat OpenShift cluster. This link will help you determine supported storage. In this demo, I have used OCS Storage.
•	A User with OpenShift Cluster and Project Administrator access
•	IBM Cloud Pak for Data Entitlement Key — Here is the link to download the entitlement key
After reviewing the system requirements and other planning information, install IBM Cloud Pak for Data by completing the provisioning clusters, setup environment variables, completing the installation task itself, and then completing the  validation of installation tasks. When complete, the Cloud Pak for Data control plane would be installed. Services are installed separately.
You use the Cloud Pak for Data command-line interface to install the Cloud Pak for Data control plane and any services that you want to run.
This guide is based on Red Hat OpenShift (ROKS) v4.6 on IBM Cloud for Cloud Pak for Data Custom. A fully managed Red Hat OpenShift 4.6 cluster installed on IBM Cloud ready for Cloud Pak for Data installation.

 ![image](https://user-images.githubusercontent.com/44421667/188652318-6349e268-6c09-4110-96ff-14518583eaac.png)


### This guide consists of four sections:
#### 1. Provisioning Of Roks:
     This section covers steps to provision ROKS for Cloud Pak for data in IBM Techzone and accessing the cluster. 
#### 2. Installing the OpenShift CLI by using the web console:
     OpenShift CLI is a mandatory tool when working with Openshift CP4D cluster. Guide for installing the OpenShift CLI by using web console is given for your reference.
#### 3. Pre-Installation Steps
    This section covers guide to generate IBM Entitlement Key and setup of various environment variables. 
    IBM Entitlement Key. key will be used to access IBM software. By accessing the IBM Entitled Registry using this key, you can easily access the IBM container software you have licensed.
    Prior to installation there are various parameters that needs to be retieved from the OpenShift Cluster, API Token etc. Setting up these parameters simplifies the installation process.
#### 4. Installation Of Cloud Pak For Data
    This section covers the installation of the Cloud pak for data. Starting from downloading the repo files, configuring the cluster to installing various services and subscriops and finally installation of cloud pak for data. 
#### 5. VALIDATION OF CLOUD PAK FOR DATA INSTALLATION
    This step covers the validation of successful installation for Cloud Pak for Data.

Click here to access the actual guide.
