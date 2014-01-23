# Scala I/O Utility Package #

Built for Scala 2.10 with JDK 6 or 7.

In your build.sbt, put:

````
libraryDependencies ++= Seq(
  "com.micronautics"  %% "scala-io"  % "0.0.1" withSources
)
````

To use:

````
import com.micronautics.io._

writeToFile("myfile.txt", "Hello, world!)

````
