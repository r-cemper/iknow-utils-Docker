# Docker for iknow-utils
Though long available the package iknow-utils never met Docker     
### Prerequisites   
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.    
### Installation    
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/r-cemper/isc-iknow-utils-Docker.git 
```
Open the terminal in this directory and run:
```
$ docker-compose up -d
```
Test from docker console
```
$ docker-compose exec iris iris session iris
USER>
```
or using **iterm**
```
http://localhost:42773/iterm/
```
### How to use it
This presents OEX package [iknow-utils](https://openexchange.intersystems.com/package/iknow-utils) using the actual IPM module    
All user documentation is found there in the [original repo](https://github.com/bdeboe/isc-iknow-utils/blob/main/README.md)  
