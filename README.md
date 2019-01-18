#Example Leshan client with Temperature and Humidity sensor

Building and running
```sh
mvn clean install
cd target
ava -jar leshan-client-sample-0.0.1-SNAPSHOT-jar-with-dependencies.jar -n <DEVICE_ENDPOINT_ID> -i <PSK_IDENTITY> -p <PSK_PASSWORD> -u <SERVER_URL>
```