callspy
=======

A simple tracing agent

Build:
gradlew jar

Run:
java -DXbootclasspath/p:javassist.jar:callspy.jar -javaagent:callspy.jar YourClazz

![java_agent_overview](java_agent_overview_min.png)
