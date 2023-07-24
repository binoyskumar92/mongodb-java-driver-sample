# Java Sync Driver Sample Code

This repository contains a sample code to test out basic CRUD operations using the Java Sync Driver.

## Getting Started

Follow the instructions below to get started with the project:

1. **Build the Project**

    Before you start, make sure to build the project.

2. **Use Create and Read Methods**

    Use the Create and Read methods provided by the Java Sync Driver to read and write content.
3. **Provide MongoDB URI**

   It's crucial to supply your MongoDB URI when running the program. This can be done through a command-line argument when starting the Java program. For example:

Enjoy testing out the basic CRUD operations with Java Sync Driver!


# Command lines

- Compile: 

```sh
mvn clean compile
```

- Run the `Create` class:

```sh
mvn compile exec:java -Dexec.mainClass="com.mongodb.quickstart.Create" -Dmongodb.uri="mongodb+srv://USERNAME:PASSWORD@cluster0-abcde.mongodb.net/test?w=majority" -Dexec.cleanupDaemonThreads=false
```

- Run the `Read` class:

```sh
mvn compile exec:java -Dexec.mainClass="com.mongodb.quickstart.Read" -Dmongodb.uri="mongodb+srv://USERNAME:PASSWORD@cluster0-abcde.mongodb.net/test?w=majority" -Dexec.cleanupDaemonThreads=false
```

- Run the `Update` class:

```sh
mvn compile exec:java -Dexec.mainClass="com.mongodb.quickstart.Update" -Dmongodb.uri="mongodb+srv://USERNAME:PASSWORD@cluster0-abcde.mongodb.net/test?w=majority" -Dexec.cleanupDaemonThreads=false
```

- Run the `Delete` class:

```sh
mvn compile exec:java -Dexec.mainClass="com.mongodb.quickstart.Delete" -Dmongodb.uri="mongodb+srv://USERNAME:PASSWORD@cluster0-abcde.mongodb.net/test?w=majority" -Dexec.cleanupDaemonThreads=false
```

# Author

Maxime Beugnet <maxime@mongodb.com>
