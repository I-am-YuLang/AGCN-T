<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

SPHDM
===
Propose an AGCN-T: a traffic flow prediction model based on temporal and spatial network dynamics.

Thank you for your interests in our work!

The dataset we ultilized for training and testin is reposited in github.

Dataset Sources
===
The traffic flow data used in the experiment comes from the Internet. The three data sets were collected by the California Department of Transportation, Seattle and Los Angeles. Among them, the ```PemsD7``` traffic data set consists of more than 39,000 sensor stations distributed in the major metropolitan areas of the California State Highway System (CalTrans) selected 228 site data. The Seattle traffic data set is composed of highways distributed in ```Seattle```,and  the system contains a speed data set of 323 sensors in 2015 with a sampling interval of 5 minutes. ```Los-Loop``` Traffic Data Set: This data set was collected in real time on the highway in Los Angeles County, and we selected 207 sensors and their traffic speeds from March 1 to March 7, 2012.
<BR>[Seattle data set](https://github.com/I-am-YuLang/Seattle-Loop-Data)
<BR>[Los-Loop data set](https://github.com/I-am-YuLang/T-GCN/tree/master/data)
<BR>[PemsD7 data set](https://github.com/I-am-YuLang/STGCN/tree/master/datasets)

Pretreatment
===
Three data sets were preprocessed in the experiment. The matrix for covariance processing of the ```LOS``` data set is ```LOS_COV```, and the matrix for PPS processing of the LOS data set is ```LOS_PPS```. The original data is ```LOS_V_207``` representing the velocity characteristic matrix, and the naming rules for the remaining ```PEMAD7``` and ```Seattle``` data sets are the same as above.

## Usage Policy and Legal Disclaimer
This dataset is being distributed only for Research purposes, under [Creative Commons Attribution-Noncommercial-ShareAlike license (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). By clicking on the download buttons, you are agreeing to use this data only for non-commercial, research, or academic applications. You may cite the above paper if you use this dataset.  
  
Contact
===
You can download this notebook as well as the well-organized dataset for training and testing. The toy example for visualization is in SPHDM Respository. If you find this work interesting and helpful to your work, please find the citation of the papers as below. Thank you very much. Any question you can email to fengjian@xust.edu.cn

@inproceedings{feng2021SPHDM, title={AGCN-T: A traffic flow prediction model for spatial-temporal network dynamics}, author={Jian Feng, Yu Lang and Rui Ma }}
