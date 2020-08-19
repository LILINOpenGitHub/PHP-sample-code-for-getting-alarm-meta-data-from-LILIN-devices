# PHP-sample-code-for-getting-alarm-meta-data-from-LILIN-devices
PHP sample code for getting alarm meta data from LILIN devices
<BR>
# The code
The sample code can be used for LILIN IP cameras/NVR/DVR and NAV recorder.  
* CGI command for IP camera <BR>

Example <BR>
http://192.168.0.200:80/getalarmmotion
<BR>

* CGI command for NVR/DVR <BR>
http://<serverIP>/getalarmmotion<channel# from 0 to 31> where the number is from channel #1 to #32, zero based
<BR>
Example <BR>
http://192.168.0.200:80/getalarmmotion01 for DVR/NVR channel #2: 
<BR>

* CGI command for Navigator's all cameras <BR>

Example <BR>
* CGI command for Navigator <BR>
http://192.168.0.200:8080/getcmxalarmmotion
