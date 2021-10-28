Assuming docker and docker-compose is installed correctly:

1. ```docker-machine start```
2.  eval "$(docker-machine env default)"
3. docker-compose -f docker-compose.development.yml -p spreeproject up
4. run docker-machine env and copy IP address
5. Open saved address on :3000 port in browser and app should be running successfully
