# PHP-sample-code-for-getting-alarm-meta-data-from-LILIN-devices
PHP sample code for getting alarm meta data from LILIN devices

# The code
The sample code can be used for LILIN IP cameras/NVR/DVR and NAV recorder.  

# CGI command for IP camera
Example
http://192.168.0.200:80/getalarmmotion

# CGI command for NVR/DVR
http://<serverIP>/getalarmmotion<channel# from 0 to 31> where the number is from channel #1 to #32, zero based
  
Example
Channel #2: http://192.168.0.200:80/getalarmmotion01  

# CGI command for Navigator's all cameras

Example
# CGI command for IP camera
http://192.168.0.200:8080/getcmxalarmmotion
