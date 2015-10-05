# websocket-test
WebSocket test with Spring &amp; Tomcat and Stomp.js

## Run
You need **gradle** installed and configured. Then just run

```gradle tomcatRun```

The app is then running under *http://localhost:8080/websocket*

To enable SSL do following:

```keytool -genkey -alias websocet_test -keyalg RSA```

This will create a .keystore file in your home dir. Link this to the
**tomcatRunWar.keyStoreFile** property.

The app is then running under *https://localhost:8443/websocket*
