# butcl
butcl is a minecraft MOD to do butterfly click for my friend.

## Build Instructions

This project uses Maven as the build tool.

### Prerequisites
- Java 8 or higher
- Maven 3.x
- Minecraft Forge 1.8.9

### Building the mod

1. Open your command-line and browse to the folder where you extracted the zip file.

2. Build the project using Maven:
   ```
   mvn clean package
   ```

3. The compiled mod will be available in the `target` directory as `butcl-1.0.jar`

### Development Setup

#### Eclipse
1. Import the project as a Maven project
2. Eclipse will automatically download dependencies

#### IntelliJ IDEA
1. Open IDEA and import the project
2. Select the `pom.xml` file and import as a Maven project
3. IntelliJ will automatically download dependencies and configure the project

### Maven Commands

- `mvn clean` - Clean the build directory
- `mvn compile` - Compile the source code
- `mvn package` - Build the jar file
- `mvn clean package` - Clean and build the project

### Dependencies

Dependencies are managed through Maven and defined in `pom.xml`. Maven will automatically download required libraries from the configured repositories.
