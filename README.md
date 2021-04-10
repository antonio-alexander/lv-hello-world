# lv-hello-world

lv-hello-world is an example library/project that provides the basic functionality for a LabVIEW application. It serves as an example for multiple distribution methods (e.g. installer, application, zip etc). Also there is an example using the built-in LabVIEW web service.

This project was used to TEST the lv-build utility and its variants, thus all the dependencies and imports, look at the lv-build repo for more information. This project is also SPECIFIC to windows, more specifically Windows 10. It has the ability to run both the webserver and the main application as admin via a labview app using the lv-bin utilities. If you're wondering, I did a little magic with the sfx using [Resource Hacker](http://www.angusj.com/resourcehacker/) and the instructions on (https://rubenalamina.mx/2013/07/17/making-a-7-zip-switchless-installer/)[https://rubenalamina.mx/2013/07/17/making-a-7-zip-switchless-installer/].