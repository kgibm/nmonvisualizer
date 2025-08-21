# NMON Visualizer

NMON Visualizer is a Java GUI tool for analyzing NMON system files from both AIX and Linux. It also parses IOStat files, IBM verbose GC logs, Perfmon CSV data and JSON data.  
For more information, including links to download an executable JAR file, see [the website](http://nmonvisualizer.github.io/nmonvisualizer/).

## Build from Source
1. Ensure a Java 11 or newer JDK is installed and configured.
1. Download [Apache Maven](https://maven.apache.org/download.cgi) and unpack into a directory, which we'll refer to as `${MAVEN_HOME}`
1. From the root directory of nmonvisualizer, run `${MAVEN_HOME}/bin/mvn clean install`. This will create an executable JAR file in the root directory.

## Running
A Java 11 JVM or newer is required. Assuming `java` is in your `$PATH`, then the executable JAR file can be run with
`java -jar NMONVisualizer_<version>.jar` or by double clicking on it in a GUI.
