 # Build server
 
You can use following commands to build and run the Napster server:

```
# Build Server
cd server
mvn package -DskipTests

# Run Server
java -jar target/server.jar
```

```
# Build Client
cd client
mvn package -DskipTests

# Run Client
java --module-path "D:\openjfx-23.0.1_windows-x64_bin-sdk\javafx-sdk-23.0.1\lib" --add-modules javafx.controls,javafx.fxml -jar target/client.jar 
```

Enjoy!
