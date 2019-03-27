# baxter-sim-demo

Requires install of docker-ce on your platform to build and run container.

Once started, do:

docker ps

to find out the name of the docker container running the vxlab-baxter2 image

Next, do:

docker exec -it <containername> bash

At the prompt, do:

source ./rosenv.sh
./simstart

Finally, to see the simulation window, run a browser on the same machine, with the URL: http://localhost:8080/vnc_auto.html
