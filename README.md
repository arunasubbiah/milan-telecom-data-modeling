# Modeling of Telecommunication CDRs to identify network usage pattern

**Background**  
Call Detail Record [CDR] describes a specific instance of a telecommunication transaction that passes through a network element. Every time a user performs a telecom activity such as send/receive SMS and calls, a CDR is generated. It contains information about the caller/sender ID, location, time, data used, etc. Millions and millions of such records are generated and is mainly used for billing purposes. Analysis and modeling of this time series data helps to identify usage patterns over a period of time and across geographical grids. This helps in decision making of resource allocation by the telecommunication company. 

**Dataset**  
Telecom Italia organized the ‘Telecom Italia Big Data Challenge’ in 2014, they provided data of two Italian areas: the city of Milan and the Province of Trentino. It is a rich, open multi-source aggregation of telecommunications, weather, news, social networks and electricity data. The data pertaining to the challenge have been released to the research teams under the Open Database License (ODbL) and is maintained by Harvard Dataverse.  

For this project we will be using 2 months (November & December) of telecommunication activity data from the city of Milan, Italy. There are 62 files consisting of CDRs collected from Nov 1,2013 to Jan 1, 2014, one file for each day. Datafiles are downloaded from https://doi.org/10.7910/DVN/EGZHFV into a folder named Data/
The city of Milan’s spatial distribution is aggregated in a grid with square cells. The area is composed of a grid overlay of 10,000 squares with size of about 235×235 meters. geojson file that provides the geographical reference of each square which composes the grid in the reference system: WGS 84—EPSG:4326 is downloaded from https://doi.org/10.7910/DVN/QJWLFU.

**Citation**  
* Barlacchi, G. et al. A multi-source dataset of urban life in the city of Milan and the Province of Trentino. Sci. Data2:150055 doi: 10.1038/sdata.2015.55 (2015)
* Telecom Italia, 2015, "Telecommunications - SMS, Call, Internet - MI", https://doi.org/10.7910/DVN/EGZHFV, Harvard Dataverse, V1  
* Telecom Italia, 2015, "Milano Grid", https://doi.org/10.7910/DVN/QJWLFU, Harvard Dataverse, V1

