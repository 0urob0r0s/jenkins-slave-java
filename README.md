# Jenkins Slave Builder for JAVA
 
**Overview**

This Dockerfile builds a Swarm based Jenkins Build Slave for JAVA.
Coupled with Rancher it will let you build a distributable, highly available Build Cluster.

**Features**

- Based on OpenJDK8, includes Node.js and NPM
- Integrates Jenkins Swarm Agent for Automatic provisioning to a Jenkins Master Node.
- Compatible with Sonarqube Scanner for code analysis.
- Compatible with Auto-scaling services.
- Node already tagged as JDK8 for restricted builds.

**Pre-requisites**

- Jenkins v2.164 Master Node
- Swarm Plugin v3.15

Please refer to Github repo USAGE.md for further instructions and examples.
