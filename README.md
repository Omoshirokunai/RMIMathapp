# RMIMathapp

# Java RMI Application

A simple java RMI application that uses localhost 

(supposed to be a school asignment)

## Compile

```
javac RemoteMathServant.java
javac IRemoteMath.java 
javac MathServer.java
javac MathClient.java
```

## RUN
in terminal run
```
rmiregistry 
java -Djava.security.policy=mathapp.policy MathServer
java -Djava.security.policy=mathapp.policy MathClient 
```
