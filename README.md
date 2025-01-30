# OpenVas
An opensource vulnerability assement scanner

Prerequiestes
* Have an installed version of an ubuntu server
* Have docker installed installed

# Installation
Download the docker compose file 
`````
curl -f -O -L https://greenbone.github.io/docs/latest/_static/docker-compose.yml "
``````
Use a text editor of your choice and make the following changes in the docker compose file before you pull it
![image](https://github.com/user-attachments/assets/409c6a12-48bf-4761-9350-d0bb23c92676)

Change the looback address of 127.0.0.1 to 0.0.0.0 
This allows all interfaces to be reached by any web browser on your network.
![image](https://github.com/user-attachments/assets/eacadee4-ee71-45ec-8441-58cb1091c6f9)

`````
docker compose pull
``````

`````
docker compose up -d 
``````




 

