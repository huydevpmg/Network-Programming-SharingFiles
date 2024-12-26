 # Build server
 
You can use following commands to build and run the Napster server:

```
# Build Server
cd server
mvn package -DskipTests

# Run Server
java -jar target/napster.server.jar
```

```
# Build Client
cd client
mvn package -DskipTests

# Run Client
java -jar target/napster.client.jar
```

Enjoy!
