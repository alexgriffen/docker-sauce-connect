 
Pre-requisites:

install docker 

pull down this repo

build image 

docker build -t .

make note of the image ID:

run the image after its been built

 

docker run -it iflanagan/sctunnels:firsttag <SAUCEUSERNAME> <SAUCEACCESSKEY> <Web/HEADLESS/RDCEU/RDCUS> <TunnelId>

Stop the container from running (i.e. kill the tunnel) 

docker containers ls

<find the container ID>
 
 docker stop <CONTAINER ID>
 
 
