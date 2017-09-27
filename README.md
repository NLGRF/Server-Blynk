# Run
```
java -jar server-0.27.1.jar -dataFolder /Path
```
## or
```
"C:\Program Files\Java\jdk1.8.0_144\bin\java" -jar server-0.27.1.jar -dataFolder /Path
```
# Change your WIFI sketch from
```
Blynk.begin(auth, SSID, pass));
```
## to
```
Blynk.begin(auth, SSID, pass, "your_host");
```
## or to
```
Blynk.begin(auth, SSID, pass, IPAddress(XXX,XXX,XXX,XXX));
```
# Login
```
email : admin@blynk.cc
password : admin
IP address : IPv4 address
Port : 8443
```
# Ex Arduino
```
  Blynk.begin(auth, ssid, pass);
  // You can also specify server:
  //Blynk.begin(auth, ssid, pass, "blynk-cloud.com", 8442);
  //Blynk.begin(auth, ssid, pass, IPAddress(192,168,1,100), 8442);
 ```