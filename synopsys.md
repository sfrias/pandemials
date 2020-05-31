Summary<BR>
Globally follow the water waste downstream of building blocks, neighborhoods, districts, departments, territorial entities..., as surveying system alert of areas of generic infection as a model for the future, in the case of SARS-CoV-2, one week before symptoms of the second cycle of infections appear.<BR>
How We Addressed This Challenge<BR>
  Today we're on the front line of a very different war from the previous ones. Official measures today:<BR>
- Health system reinforcing: very expensive and slow to scale up/down requirements.<BR>
- Social distancing, preserve risk groups: freedom and mood affectations for mid/long term->Heavy social cost.<BR>
- Too many asimptomatic people: screening for infection/antibodies: Very expensive, not always sensitive to antigens, and with infection analysis times in periods of system stress that are too long, and false positives increases up to 20% before and after day of most viral load (around of 8th day after infection).<BR>
- Grouping inmunity, that is lower still today to a good protection in front of disease spread.<BR><BR>
  A detail that nobody expected: surveying system is independent of health system. We can associate, but only on clinical issues.
  Really, the control of infection with high rate of asymptomatic cases can be hard on high density areas, with residential, transport environments, labor areas, malls, leisure centers and other specific fixed or temporary people accumulation areas.<BR>
  The global goal:  is to obtain a trend for a community, establish thresholds to activate/deactivate complimentary measures, after process the stream of samples, binded of points associated to a specific area. This data streams, were processed (normalization, factor, variance,...), and convert value of measures to a prevalent value for population associated, for example to anticipated decision making. Is a process that contains a complex dependencies.<BR>
How We Developed This Project<BR>
  Find concentration of SARS-CoV-2 genetic signature on waste water could be a sensitive and early warning, to spot a rebound in cases as soon as this fall can be a measure of viral prevalence, for decision making. On sewage there are virus particles, mostly intact, but are not longer infective; is a secure method (0).<BR>
  Several labs have demonstrated with a proof of concept the ability to detect the SARS-CoV-2 RNA in wastewater, about a week before severe simptoms detected(3).<BR>
   First we would collect sewage samples from local sample points, running them RT-PCR (process that creates millions of copies of viral RNA), and then a process that looks for specific markers on SARS-CoV-2, to distinguish this particular virus from all the other possible microbes in wastewater samples (1) (2).  Each sample can be a snapshot of that community's health, a measurement of what's happening in the community. <BR>
  But not only waste water measures play on model, other factors as waste water/hydrological paths, flow rate, treatment nodes,climate,...and other plays.  Waste water model will include other animal species, that probably in future epidemic issues can spread the infection.<BR>
 Our primary goal as team is make a simple data model to calculate trends on low level of infection curve, and establish thresholds as a long-term target, can be more simple and cheap in front of individual screening, or other measures.  Process local opendata with sample results with python to generate a MVP, to integrate this info on a GiS browser information.<BR>
  Most part of Earth's ground has not opendata for watersheds, water downstream, catch and discharges of subterranean/surface water for human use. We'll try to use Satelite data to set sample points and their nexus with upstream water.<BR>
+ Global Estimates of River Flow Travel Times and Implications for Low‐Latency Satellite Data<BR>
+  WMS thematic layers on NEO NASA Earth Observation<BR>
+  Application of remote sensing, VIC18 implementation on watersheds approach.<BR> 
+  Application of TWI and NWDI to mark downstream and topographic radar to mark watersheds. Also we can try SWIR and false color images.<BR>
+  Integrate GiS to mark sample points, data sampled, alerts and warnings.<BR>
QGIS or SNAP use to represent measures and variations. Generate alerts or warnings when we're out of threshold would be nice.
  
  
  
References: List the data and resources used in your project:<BR>
https://land.copernicus.eu<BR>
https://www.scdhec.gov/environment/environmental-data-maps-reports/gis-apps-data<BR>
https://arset.gsfc.nasa.gov/water/webinars/VIC18<BR>
https://arset.gsfc.nasa.gov/water/webinars/drought17<BR>
https://datasetsearch.research.google.com/<BR>
ftp://e0srp01u.ecs.nasa.gov/srtm/version2/SRTM3/<BR>
http://srtm.csi.cgiar.org/wp-content/uploads/files/250m/<BR>
https://cgiarcsi.community/2017/11/20/mapping-the-rise-of-wastewater-irrigated-urban-peri-urban-agriculture-in-india/<BR>
http://www.esa-sen2agri.org/<BR>
http://www.naturalearthdata.com/downloads/<BR>
Fragments from Planet Team (2018). Planet Application Program Interface: In Space for Life on Earth. San Francisco, CA. https://api.planet.com<BR>
(3) Four researchers from the Water Research Institute in the Netherlands (KWR Water Research Institute) discussed this subject and examined the samples of wastewater collected from 7 different cities. In the sample test with the RT-PCR protocol, the researchers tested 3 fragments (N-1,2,3) of the "nucleocapsid" protein gene and a fragment (E) of the "envelope" protein gene. The first samples were taken on February 6, 3 weeks before the first Covid-19 case reported in the Netherlands. No trailer was detected. In the samples taken later on March 5, the N1 trailer was detected in 5 cities. In the samples taken on March 15, the N1 trailer showed positive results in 6 cities, while the N3 and E fragments in 5 cities. Thus, the detection of the virus was reported for the first time with sewage waste water. Same for Conneticut Research, and Paris processing wartewater samples previously stored at 4ºC.<BR>
Papers:<BR>
(0) Presence of SARS-Coronavirus-2 RNA in Sewage and Correlation with  Reported COVID-19 Prevalence in the Early Stage of the Epidemic in The  Netherlands.Gertjan Medema, Leo Heijnen, Goffe Elsinga, Ronald Italiaander, and Anke Brouwer.Environmental Science & Technology Letters. DOI: 10.1021/acs.estlett.0c00357<BR>
(1) Presence of SARS-Coronavirus-2 in sewage. Gertjan Medema, Leo Heijnen, Goffe Elsinga, Ronald Italiaander, Anke Brouwer  doi: https://doi.org/10.1101/2020.03.29.20045880 <BR>
(2) SARS-CoV-2 titers in wastewater are higher than expected from clinically confirmed cases. Fuqing Wu, Amy Xiao, Jianbo Zhang, Xiaoqiong Gu, Wei Lin Lee, Kathryn Kauffman, William Hanage, Mariana Matus, Newsha Ghaeli, Noriko Endo, Claire Duvallet, Katya Moniz, Timothy Erickson, Peter Chai, Janelle Thompson, Eric Alm. doi: https://doi.org/10.1101/2020.04.05.20051540 <BR>
(4)Evaluation of lockdown impact on SARS-CoV-2 dynamics through viral genome quantification in Paris wastewaters. Sebastien Wurtzer, Vincent Marechal, Jean-Marie Mouchel, Yvon Maday, Remy Teyssou, Elise Richard, Jean Luc Almayrac,Laurent Moulin ORCID Profile  doi: https://doi.org/10.1101/2020.04.12.20062679<BR>
Add some tags so we can categorize your project<BR>
#covid_19 #space4good #sewage4covid # #fastresponse #spaceapps
