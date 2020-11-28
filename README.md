# java-basic


## Build the Java Source

`javac -d ./dist/ src/App.java`

## Make a jar

`jar -cf dist/App.jar dist/App.class`

## Run the Java Classes

`java -cp dist App`

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies
- `dist`: the folder to keep built bytecode java classes and jars

## Dependency Management

The `JAVA DEPENDENCIES` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-pack/blob/master/release-notes/v0.9.0.md#work-with-jar-files-directly).
