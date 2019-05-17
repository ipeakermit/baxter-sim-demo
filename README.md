# baxter-sim-demo

Requires install of docker-ce on your platform to build and run container.

Build using:

./build

Run using:

./run

This will start two containers in the background: an X11 display container and a Baxter simulator. Once started, do:

docker ps

to find out the name of the docker container running the Baxter simulator (vxlab-baxter2) image

Next, do:

docker exec -it vxlab-baxter2 bash

At the prompt, do:

source ./rosenv.sh

./simstart

Finally, to see the simulation window, run a browser on the same machine, with the URL: http://localhost:8080/vnc_auto.html
