# httpsspringboot
spring boot https config
To generate keystore

```
keytool -genkeypair -alias tomcat -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore keystore.p12 -validity 3650 -storepass <password>

```
