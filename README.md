# iDaaS Lunch and Learns
In order to enable resources to be able to understand the iDaaS Design Pattern Framework and Accelerator
we felt it best to ensure we focused on a maintainable list of Lunch and Learns and a means and way to publish them for ease of use and maintenance.
<br/>
# The Intent of Lunch and Learns
When desigining these we went to numerous resources within the healthcare industry and looked at countless other ways organizations are delivering education materials on similiar items. We ultimately decided on taking what we felt with the best of everything.

1. We will be keeping ANY watchable content to less than 30 minutes, the optimal time for any content to watch we are focused on keeping to 15 minutes or less.
2. We wanted to maintain our strong open source roots, so we have decided to publish all the base content through Git Hub. Where we might face a potential limitation is the potentially large size for things like video/audio files.

# The Lunch and Learn Course Track
The following section covers the entire Lunch and Lean Course Track.

| Course Level | Description |
| ------------ | ----------- |
| 100      | General Background |
| 200      | Basic Messaging and Data Routing |
| 300      | Basic Messaging and Data Processing | 
| 400      | Auditing and Insight |
<br/>

All Lunch and Learn Activities Leverage the existing iDaaS-Demos repository located
at [https://github.com/RedHat-Healthcare/iDaaS-Demos](iDaaS-Demos).

## Pre-Requisites
For all iDaaS design patterns it should be assumed that you will either install as part of this effort, or have the following:

1. An existing Kafka (or some flavor of it) up and running. Red Hat currently implements AMQ-Streams based on Apache Kafka; however, we
have implemented iDaaS with numerous Kafka implementations. Please see the following files we have included to try and help:<br/>
[Kafka](https://github.com/RedHat-Healthcare/iDaaS-Demos/blob/master/Kafka.md)<br/>
[Kafka on Windows](https://github.com/RedHat-Healthcare/iDaaS-Demos/blob/master/KafkaWindows.md)
2. Some understanding of building, deploying Java artifacts and the commands associated
3. An internet connection with active internet connectivity, this is to ensure that if any Maven commands are
run and any libraries need to be pulled down they can.

We also leverage [Kafka Tools](https://kafkatool.com/) to help us show Kafka details and transactions; however, you can leverage
code or various other Kafka technologies ot view the topics.

# General Architecture
The following section is meant to define and also help visualize the general architecture within an healthcare  
(payer/provider/life sciences) implementation.
![https://github.com/RedHat-Healthcare/iDAAS/blob/master/content/images/iDAAS-Platform/iDAAS%20Platform%20-%20Visuals%20-%20iDaaS%20Data%20Flow%20-%20Detailed.png](https://github.com/RedHat-Healthcare/iDAAS/blob/master/content/images/iDAAS-Platform/iDAAS%20Platform%20-%20Visuals%20-%20iDaaS%20Data%20Flow%20-%20Detailed.png)

As you look at this visual notice we DO NOT take a target data position to build, we believe that is a customers to shape for their specific business needs. We are working on creating a demonstration to  
show a sample endpoint for strickly closing the loop on data processing. <br/>

## 100 - General Background
101 -	<a href="https://www.screencast.com/users/RedHatHealthcare/folders/Videos%20-%20iDaaS/media/ca3bcf23-e655-4cdc-a7e3-a82d42845194" target="_blank">
Open Source in Healthcare</a><br/>
102 - <a href="https://www.screencast.com/users/RedHatHealthcare/folders/Videos%20-%20iDaaS/media/854a7f94-82a2-4e9f-ba9b-947efddf6799" target="_blank">
What is iDaaS</a><br/>
103	- <a href="https://www.screencast.com/users/RedHatHealthcare/folders/Videos%20-%20iDaaS/media/d9f299c9-40f2-442e-bdb2-d93380b574a7" target="_blank">
Git Hub General Improvements</a> <br/>
104 - <a href="https://www.screencast.com/users/RedHatHealthcare/folders/Videos%20-%20iDaaS/media/1b2ae439-9eb7-4250-bbdc-271c26d76292" target="_blank">
Git Hub Repository Geenral Overview</a> <br/>

## 200 - Basic Messaging and Data Routing 
201	iDaaS Connect HL7 - <br/>
202 iDaaS Connect FHIR - 	<br/>
203 iDaaS Connect Third Party -<br/>
204 Basic Messaging and Routing	<br/>

## 300 - Basic Messaging and Data Processing
301	iDaaS Connect HL7 - <br/>
302 iDaaS Connect FHIR - 	<br/>
303 iDaaS DREAM (Intelligent Routing) - X <br/>

## 400 - Auditing and Insight
401 iDaaS KIC 