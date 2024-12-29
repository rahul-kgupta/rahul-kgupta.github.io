---
layout: page
permalink: /code/
tags: [code]
modified: 29-12-2024
comments: false
---


### Synthetic distribution networks of Switzerland
We provide synthetically generated medium voltage (MV) power distribution network models for the whole of Switzerland. The networks are generared using the method proposed in [R. Gupta et. al](https://doi.org/10.1016/j.apenergy.2020.116010) In brief, the networks are estimated using an unsupervised method to infer the topologies and characteristics of the MV networks starting from publicly available highly resolved geo-refrenced energy demand and locations of the extra-high-voltage (EHV) substations. The energy demand is estimated from the [Swiss Federeal Office of Topography](https://www.swisstopo.admin.ch/en) and the EHV susbtations are taken from [ENTSOE](https://www.entsoe.eu/). In total, 776 MV networks are generated covering the whole Switzerland.
The networks can be downloaded from [Link](https://github.com/DESL-EPFL/Estimated-Medium-Voltage-Distribution-Network-Models-for-Switzerland)

### Photovoltaic and Load data
his repository provides time-series of global horizontal irradiance (GHI) and PV production measurements of solar panels at the EPFL's Distributed Electrical Systems Laboratory, Switzerland.

The time-series is recorded over last 5-years. The GHI is measured via a pyranometer installed on the roof-top of the DESL building. The specification of pyranometer are detailed in [Scolari, E. 2019](https://infoscience.epfl.ch/server/api/core/bitstreams/61c4e154-ca10-48ef-92e5-e5668a94b2b1/content). The PV power production is measured on the AC side. During the course of last five years, several instances might have missing data due to reasons related to maintenance etc. of the sensors. Addionally, it contains 1-seconds resolution data for June, July, Dec 2021 and Jan 2022.
The data is hosted on [DESL-Github](https://github.com/DESL-EPFL/DESL-Photovoltaic-timeseries)

