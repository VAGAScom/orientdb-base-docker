OrientDB 2.0 (Base)
===================

[OrientDB](http://www.orientechnologies.com/orientdb/) is a distributed graph database (actually, a Multi-Model DBMS).

This image is just OrientDB downloaded. It's intention is to be a base for other OrientDB Docker images, so you don't have to download and build it at every new image.

The installation
================
 - It uses OpenJDK-7;
 - OrientDB is installed at /opt/orientdb;
 - Config files are in /opt/orientdb/config;
 - The example database "GratefulDeadConcerts" was removed;
 - Default ports for OrientDB are 2424 (binary) and 2480 (Studio and REST).