# Biopar Processing on NextGeoss platform - Notebook

The NextGEOSS project, a European contribution to GEOSS (Global Earth Observation System of Systems), is developing the next generation centralised European hub for Earth Observation data, where the users can connect to access data and deploy EO-based applications. The concept revolves around providing the data and resources to the users communities, together with Cloud resources, seamlessly connected to provide an integrated ecosystem for supporting applications. 

Within the agricultural community, the Copernicus Sentinel-2 mission is an important asset for crop monitoring, making field based monitoring possible. In the *Food Security* pilot of NextGEOSS we aim to demonstrate how the NextGEOSS services can be used to facilitate the use of Sentinel-2 data for Crop Monitoring. A first step in this process was building a processing workflow on the NextGEOSS platform, called the biopar processing. This workflow will collect Sentinel-2 data from the NextGEOSS catalog and process it into vegetation indices. These indices provide useful crop information such as its health, the status in the growing season, ...

This notebook is build to demonstrate how this processing workflow can be integrated in another application or process. This is done by using the WPS endpoint that is made available through the NextGEOSS services. This WPS endpoint allows for an easy integration and flexibility to process Sentinel-2 data over any specific spatial and temporal dimension. 

## Prerequisites

This notebook is a demonstrator of the NextGEOSS services. Therefor the **WPS is not publically accessible**. The usage of the WPS client is limited to access by authorized IP addresses and NextGEOSS users only. 

## References

* This notebook was referenced on [Twitter](https://twitter.com/gp3dr0/status/1007167024831836160)
* [NextGEOSS](https://nextgeoss.eu/) website
* [Food Security Pilot](https://nextgeoss.eu/pilots/food-security/)

