# Cassandra docker cheatsheet

```Bash
#========status=============
#Active containers
docker ps
#Container Utilization
docker stats
#Container Details
docker inspect dse
#NodeTool Status
docker exec -it dse nodetool status

#========== Logs ==========
#Server Logs
docker logs dse
#System Out
docker exec -it dse cat /var/log/cassandra/system.log
#Studio Logs
docker logs studio

#==== Start/Stop/Remove ====
#Start Container
docker start dse
#Stop Container
docker stop dse
#Remove Container
docker remove dse

#======= Additional =======
#Contaier IPAddress
docker inspect dse | grep IPAddress
#CQL (Requires IPAddress from above)
docker exec -it dse cqlsh [IPAddress]
#Bash
docker exec -it dse bash
```
