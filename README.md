<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

AGCN-T
===
A spatio-temporal network dynamic traffic flow prediction model (AGCN-T) method is proposed for multi-step traffic flow prediction

Thank you for your interests in our work!

The dataset used by AGCN-T for training and testing is deposited here in AGCN-T/dataset.

Dataset Sources
===
The traffic flow data used in the experiment comes from the Internet. The three data sets were collected by the California Department of Transportation, Seattle and Los Angeles. Among them.
* the ```PemsD7``` traffic data set consists of more than 39,000 sensor stations distributed in the major metropolitan areas of the California State Highway System (CalTrans) selected 228 site data. 
    * ```PemsD7_V_228.csv``` represents the speed characteristic matrix collected by the California State Highway System (CalTrans) sensor
    * ```PemsD7_V_228.csv``` represents the adjacency matrix of the road network of California highways

* The Seattle traffic data set is composed of highways distributed in ```Seattle```,and  the system contains a speed data set of 323 sensors in 2015 with a sampling interval of 5 minutes.
    *```Seattle_V_323.csv```  represents the speed characteristic matrix collected by Seattle highway sensors
    *```Seattle_V_323.csv```  represents the adjacency matrix of the road network of Seattle highway

* ```Los-Loop``` Traffic Data Set: This data set was collected in real time on the highway in Los Angeles County, and we selected 207 sensors and their traffic speeds from March 1 to March 7, 2012
    *```Los_V_207.csv```represents the velocity characteristic matrix collected by the sensor
    *```Los_W_207.csv```  represents the road network adjacency matrix of Los Angeles County
  

## Usage Policy and Legal Disclaimer
This dataset is being distributed only for Research purposes, under [Creative Commons Attribution-Noncommercial-ShareAlike license (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). By clicking on the download buttons, you are agreeing to use this data only for non-commercial, research, or academic applications. You may cite the above paper if you use this dataset.  
  
Contact
===
You can download this notebook as well as the well-organized dataset for training and testing. The toy example for visualization is in SPHDM Respository. If you find this work interesting and helpful to your work, please find the citation of the papers as below. Thank you very much. Any question you can email to fengjian@xust.edu.cn

@inproceedings{feng2021AGCN-T, title={AGCN-T: A traffic flow prediction model for spatial-temporal network dynamics}, author={Jian Feng, Yu Lang and Rui Ma }}
