 
Pre-requisites:

install docker 

pull down this repo

change directory to where the repo was pulled down from:

build image 

docker build -t .

make note of the image ID:

run the image after its been built

docker run --name <name> <imageID> 

Or pull down the container and run directly 

docker run -it iflanagan/sctunnels:firsttag <SAUCEUSERNAME> <SAUCEACCESSKEY> <Web/HEADLESS/RDCEU/RDCUS> <TunnelId>

Stop the container from running (i.e. kill the tunnel) 

docker container ls

<find the container ID>
 
 docker stop <CONTAINER ID>
 
 
