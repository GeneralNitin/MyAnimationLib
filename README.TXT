==================
HOW TO USE?
==================


Import -> import AcutalProgramming.AnimationV2; // ActualProgramming My YouTube Channel
Object -> AnimationV2 AC = new AnimationV2(); // Version 2 has fade in and out effects as well, however still needs refining
Calling -> AC.jPanelXLeft(int start, int stop, int delay, int increment, JPanel jPanel);

Additional info -> // Start, Stop are the Coordinates; Delay is the time it takes to finish the animation; Increment is by how much                           it moves after a loop; SwingComponent Object.

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "MyAnimationLib.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
