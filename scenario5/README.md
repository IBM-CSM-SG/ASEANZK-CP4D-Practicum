# ASEANZK Cloud Pak for Data – Practicum Scenario 5

## IBM CP4D Installation & Configuration In Openshift

  ### Introduction
  IBM Cloud Pak for Data is a unified data and AI platform that connects the right data, at the right time, to the right people anywhere. Running on the  Red Hat OpenShift platform simplifies data access, automates data discovery and curation, and safeguards sensitive information by automating policy   enforcement for all users in your organization. Make better data-driven decisions and lay the foundation for AI with a data fabric that connects   siloed data on-premises or across multiple clouds without data movement. Discover actionable insights and apply trusted data to build, run, automate and manage AI models.

  This document provides step-by-step instructions to install IBM Cloud Pak for Data on the Red Hat OpenShift cluster. However, before we begin the installation, let’s ensure the following assumptions and pre-requisite are met.

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

### Installing IBM cloud pak for data
  #### Setup IBM Techzone ROKS Cluster
    In this scenario
    ##### Provisioning cluster
    ##### Access to the cluster
  #### Pre-installation steps
    ##### IBM entitlement key
    ##### Setup environment variables
  #### Installation of cloud pak for data
    ##### Download repo files
    ##### Setting up projects (namespaces) on red hat openshift container platform
    ##### Configuring your cluster to pull cloud pak for data images
    ##### Creating catalog sources
    ##### Installing IBM cloud pak foundational services
    ##### Creating the license service operator subscription
    ##### Creating an operator subscription for the scheduling service
    ##### Creating an operator subscription for the IBM cloud pak for data platform operator
    ##### Installing cloud pak for data serviices
  #### Validation of cloud pak for data installation
    ##### Access the cloud pak for data
