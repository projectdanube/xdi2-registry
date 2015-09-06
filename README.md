<a href="http://projectdanube.org/" target="_blank"><img src="http://projectdanube.github.com/xdi2/images/projectdanube_logo.png" align="right"></a>
<img src="http://projectdanube.github.com/xdi2/images/logo64.png"><br>

This is a configuration profile of the [XDI2](http://github.com/projectdanube/xdi2) server for 
hosting a registry of XDI names and XDI numbers. The XDI vision entails a decentralized
discovery notion, where any peer can act as a registry.

### Information

* [Configuration](https://github.com/projectdanube/xdi2-registry/wiki/Configuration)
* [The registry graph](https://github.com/projectdanube/xdi2-registry/wiki/The-registry-graph)

### How to build

First, you need to build the main [XDI2](http://github.com/projectdanube/xdi2) project.

After that, just run

    mvn clean install jetty:run

Then use an XDI client to send XDI messages to the "registry" graph

    http://localhost:9400/registry

Or access the server's status page at

	http://localhost:9400/ (disabled in applicationContext.xml by default)

### Community

Google Group: http://groups.google.com/group/xdi2

IRC: irc://irc.freenode.net:6667/xdi
