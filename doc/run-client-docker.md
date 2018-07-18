To run the ignition wallet client in a docker container:

- Install docker https://docs.docker.com/install/
- Run :
`docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v <absolute-path-to-ignition-sources>:/project ignitioncoin/run_wallet`

Note : 

If you previously built sources for another OS, you'll need to run scripts/clean.sh
