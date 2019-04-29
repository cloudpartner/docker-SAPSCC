# SAP Cloud Connector in a Linux container with JAVA 8

The Dockerfile contains version **2.11.3 of SAP Cloud Connector**, and ready to use in containers. 
Just check for  the appropriate *dockers tags before pulling*. 

Notice that SAPSCC version may be manipulated through the environment variables below:

* SCC_VERSION_MAJOR
* SCC_VERSION_MINOR
* SCC_VERSION_BUILD
* SCC_VERSION_ID

# Available package manager

* zypper

# Installed packages

Package         | Version   | Description                                      | Size (after its installation)
:-------------- |:---------:|:------------------------------------------------:|------------------------------:
bash            | 5.5.0     | The GNU Bourne Again shell                       | ~1.05MB
wget            | 1.20.3    | A network utility to retrieve files from the Web | ~476KB
unzip           | 6.0       | Extract PKZIP-compatible .zip files              | 244KB

# Docker Tags
* hcc:2.11.3
