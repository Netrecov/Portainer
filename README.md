# Portainer

this will cover isntall portainer once you have docker isntalled

sudo docker pull portainer/portainer-ce:latest || error "Failed to pull latest Portainer docker image!"
sudo docker run -d -p 9000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest || error "Failed to run Portainer docker image!"

Pi-Hosted Portainer Template V2
Discord Youtube Twitter URL hacktoberfest

This repository is a collection of tutorials for hosting a variety of server applications using Docker and Portainer.

App Template for Portainer
alt text

Installation
Run install-docker.sh, to install docker, and add the current user to the docker usergroup.

wget -qO- https://git.io/JwUkc | bash
# need to reboot/logout for changes to take effect
sudo reboot
After a reboot, run install-portainer.sh, to install Portainer.io

wget -qO- https://git.io/JwUnf | bash
# to update portainer, run this command
wget -qO- https://git.io/JwUlY | bash
Click Settings, in the bottom-left corner, and paste the Portainer v2 json file link from below into the "App Templates" box.

You're done! Now just click App Templates and deploy applications!

Versions
Application	URL
Portainer v2	https://raw.githubusercontent.com/novaspirit/pi-hosted/master/pi-hosted_template/template/portainer-v2.json
Pi-Hosted YouTube series
Pi-Hosted Playlist

Contributors
See the list of contributors who participated in this project.

Acknowledgment
based template on SelfHosted Portainer App Template
