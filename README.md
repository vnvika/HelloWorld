# What is the program?
It is a simple program written in **Java**. Output the result to the console.
## How will it launch this program?
You need to install and unpack folder. 

In the console, go to the repository folder and enter:

`mkdir bin`

After input:

`javac -d bin src/main/*.java src/entities/*.java`

And then you can launch program:

`java -classpath ./bin main.Main`

After a successful launch, you will see:

`Hello vnvika`

## How to create a jar file?
You should go to the bin folder in the console:

`cd bin`

After input:

`jar cvfe HelloWorld.jar main.Main main.Main.class entities.User.class`

And launch a jar file:

`java -jar HelloWorld.jar`

After a successful launch, you will see:

`Hello vnvika`

## How to launch with apache-commons.jar lib?

You should go back to the repository folder and enter:

`java -jar bin/HelloWorld.jar lib/apache-commons.jar`

After a successful launch, you will see:

`Hello vnvika`
