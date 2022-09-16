
# ASEANZK Cloud Pak for Data – Practicum Scenario 1

[**Use Case**](#_Toc109841328)

[**Scenario Description**](#_Toc109841329)

[**High Level Architecture**](#_Toc109841330)

[**Product Used**](#_Toc109841331)

[**Environment Details**](#_Toc109841332)

[**Reference Implementation Steps**](#_Toc109841333)

------

<span id="_Toc109841328" class="anchor"></span>
<font size="5">**Use Case**</font>

Data Integration / Data Virtualization

<span id="_Toc109841329" class="anchor"></span>
<font size="5">**Scenario Description**</font>

SAN Telecom is a top Telco operator in Europe, they store their customers data on multiple dbs. Some of them are on cloud and others are on prem. They have already developed some models and dashboards using IBM SPSS Modeler and open-source tools and cloud pak for data (public cloud version).  SAN Telecom has recently acquired Cloud Pak for Data v4 and are planning to utilize its key features to achieve the following goals ​:

- 1. Data Governance​
- 2. Run analytics on multiple data sources without clogging their network by moving all data to a central location​
- 3. Migrate existing work from SPSS Modeler and public cloud to the new Cloud Pak for Data​

SAN Telecom is currently using the data coming from multiple sources to build their models and dashboards. They run one large query overnight to bring
the data from the two sources into a central location before running a series of data processing jobs to get the final dataset to be used on
the dashboard.

Your objective is to use IBM Cloud Pak for Data features to avoid the need of running the bottleneck query. The main features to focus on here
are Data Virtualization and Watson Query.

​<span id="_Toc109841330" class="anchor"></span>
<font size="5">**High Level Architecture**</font>

Below is the high level architecture that we plan to implement as part
of this scenario.

<img src="./media/image1.png" style="width:4.52188in;height:2.78114in" alt="Architecture" />

<span id="_Toc109841331" class="anchor"></span>
<font size="5">**Product Used**</font>

The list of products used in the solution are highlighted below.

<img src="./media/image2.png" style="width:6.1923in;height:3.47067in" alt="Product List" />

<span id="_Toc109841332" class="anchor"></span>
<font size="5">**Environment Details**</font>

Use the below IBM Cloud Env Details for Scenario Implementation.
Credentials will be available in the slack Channel.

**TBD**

<span id="_Toc109841333" class="anchor"></span>
<font size="5"> **Reference Implementation Steps** </font>

Click [**Here**](scenario1-rosa.pdf) to try the Data Virtualization Lab on IBM Cloud Pak for Data using IBM ROSA Cluster on AWS

Click [**Here**](scenario1-SaaS.pdf) to try the Data Virtualization Lab on IBM Cloud Pak for Data as Service on IBM Cloud.

