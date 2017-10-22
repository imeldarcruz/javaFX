# javaFX
This code SHOULD work, I know that it worked on the computers at the lab at school. The issue had something to do with fact that the new edition of Eclipse did not recognize Javafx library(?) however I don't know how to add it in.


Pre-requisites:

* Java development kit (JDK) version 1.8+ is required, if unsure, follow this [instruction](https://www.java.com/en/download/help/version_manual.xml) to check
* if JDK is not installed, see this [video](https://www.youtube.com/watch?v=CDjTBGiB4zs) to install JDK
* JavaFX is included as part of JDK 1.8

To compile and run, it maybe simpler to use only command line (instead of eclipse), see this [video](https://youtu.be/CDjTBGiB4zs?t=9m54s)

```
# in command prompt, type in the following
# after compiling, you should see FontDemo.class in the same directory
javac FontDemo.java

# run the program
java -cp . FontDemo
