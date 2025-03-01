# HGV-Middleware

This Repo contains all middleware being used to turn the Arduino Json into useable data by the Website and other Code, Here is all the config and setup files used for the docker container used in the project. each have a docker compose file which was used to create the container except for NodeRed which just used the Docker command on the website. These folders also contain some configuration files for NodeRed and Grafana just for backup. most of these files shouldn't need to be touch unless something breaks as most of this should already be running.

## Ascessing Container

if on REMS006 you ascess the container via entering localhost and then the container port. if on the Network but not on REMS006 you just enter the PC ip address + port instead.

The Ports you should know
| Container | Port |
| ------------- |:-------------:|
| Portainer | :9443 |
| NodeRed | :1880 |
| Prometheus | :9090 |
| Grafana | :3000 |


## Project Flowchart
![image](https://github.com/user-attachments/assets/45a03fcc-b4f9-4d8c-a0a4-028e5870132a)


## Passwords

Passwords for some of the containers can be found either on the Discord, REMS006 in the Password Manager or HGV Wiki
