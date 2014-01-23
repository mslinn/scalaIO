# Scala I/O Utility Package #

Built for Scala 2.10 with JDK 6 or 7.

In your build.sbt, put:

````
libraryDependencies ++= Seq(
  "com.micronautics"  %% "scalaio"  % "0.1.0-SNAPSHOT" withSources
)

resolvers ++= Seq(
  Resolver.url("play-plugin-releases",  new URL("http://repo.scala-sbt.org/scalasbt/sbt-plugin-releases/"))(Resolver.mavenStlePatterns),
  Resolver.url("play-plugin-snapshots", new URL("http://repo.scala-sbt.org/scalasbt/sbt-plugin-snapshots/"))(Resolver.mavenStlePatterns)
)

````

To use:

````
import com.micronautics.io._

writeToFile("myfile.txt", "Hello, world!)

````
