# Greenbone Vulnerability Management with OpenVAS

This setup is based on Greenbone Vulnerability Management and OpenVAS. We have made improvements to help stability and functionality.

## Documentation
* [Instrucciones de Uso](https://mind.indra.es/pages/viewpage.action?pageId=489037570) (
[Fuente Original](https://securecompliance.gitbook.io/projects/openvas-greenbone-deployment-full-guide))

## You can view our old documentation in our wiki, but we are converting everything to gitbook.
* [View old Wiki](https://github.com/DigitalLabsIndra/GVM-Docker/wiki)

## Architecture

The key points to take away from the diagram below, is the way our setup establishes connection with the remote sensor, and the available ports on the GMV-Docker container. You can still use any add on tools you've used in the past with OpenVAS on 9390. One of the latest/best upgrades allows you connect directly to postgres using your favorite database tool. 

![GVM Container Architecture](https://raw.githubusercontent.com/DigitalLabsIndra/GVM-Docker/master/SCS-GVM-Docker.svg)



