# Home Asssistant Configuration

Open source home automation that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts. 

## Hassio Hardware Configuration
- Intel NUC i3 Gen 7 
- Ubunbu Server 18.04
- Docker CE. 

## Hassio Installation on Ubuntu 18.04 and Docker CE
The [Hassio](https://github.com/noodlemctwoodle/hassio/wiki/Install-Hass.io) guide describes how to install Hass.io on Ubuntu Server running Docker CE, configure custom storage paths using the pre-created script from [Home Assistant](https://github.com/home-assistant/hassio-build/blob/master/install/hassio_install) and expose to the internet using NGINX reverse proxy.

## NGINX Reverse Proxy for Hass.io and additional dockler contaianers
The [NGINX and Lets Encrypt](https://github.com/noodlemctwoodle/hassio/wiki/Guide---NGINX-&-Lets-Encrypt) configuration sets up a reverse proxy to expose containers to [Home Assistant](https://www.home-assistant.io/) front end without HTTPS script errors.

## Check out my Wiki
Further information and guides can be found on my [wiki](https://github.com/noodlemctwoodle/hassio/wiki)

## Screenshots of my front end
![hassio1](https://raw.githubusercontent.com/noodlemctwoodle/hassio/master/www/github/screenshots/lounge.png)
![hassio2](https://raw.githubusercontent.com/noodlemctwoodle/hassio/master/www/github/screenshots/kitchen.png)
![hassio3](https://raw.githubusercontent.com/noodlemctwoodle/hassio/master/www/github/screenshots/grafana.png)