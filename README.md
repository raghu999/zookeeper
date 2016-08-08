#Dockerized zookeeper

#Usage

#Env variables

#Single-node super-simple setup:

`docker run -d -p 2181:2181 -e ZK_CONFIG=clientPort=2181 -e ZK_ID=1 raghuchalla/zookeeper`


