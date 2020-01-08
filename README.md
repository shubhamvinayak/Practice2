# Practice2

### Docker images used to run graybox
Two separate images are created to run graybox in chrome and firefox.

**Image 1: selenium-chrome**

         **selenium-chrome** image to run graybox test in headless chrome, which uses base image 
         **selenium/standalone-chrome:3.141.59** from docker hub. It has preinstalled Google Chrome v78.0.3904.70, 
         ChromeDriver v78.0.3904.70 and node v13.0 is installed.


**Image 2: selenium-firefox**hkg

         **selenium-firefox** image to run graybox test in headless firefox, which uses base image
         **selenium/standalone-firefox:3.141** from docker hub. It has preinstalled Mozilla Firefox v70.0,
         geckodriver v0.26.0 and node v13.0 is installed.

Link to [repository](https://github.cerner.com/MPagesEcosystem/mpages-docker-image) and created images are maintained in [Jfrog-artifactory](https://docker-snapshot.cernerrepos.net/webapp/#/artifacts/browse/simple/General/docker-snapshot/mpages-docker-images).
