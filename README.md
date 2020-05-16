# docker_node_js
Simple Docker Node JS Container - A boiler plate repo to build from.

## Docker Commands:

- Build: docker build -t test-node-docker .
- Run: docker run -d -p 9000:3000 node-docker
- Check its running: docker ps
- Review all Docker Containers: docker images
- Stop Container: docker stop

## Notes:

Build: docker build -t test-node-docker .

Will start up a Docker container based off our node-docker docker image and expose it on port 9000 on our machine. The -d flag specifies that we wish to run this in a detached mode which means that the docker container will run in the background on our host machine.

In order to view all of the running containers on your local machine, type docker ps. This should show our node-docker container running and the ports that it’s listening to.

