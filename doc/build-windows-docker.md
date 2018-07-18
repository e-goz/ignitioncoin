To build windows binaries in a docker container (no need to install any dependency) :

- Install docker https://docs.docker.com/install/
- Run
`docker run -ti -v <absolute-path-to-ignition-sources>:/project ignitioncoin/build_windows`

Note :

If you previously built sources for another OS, you'll need to run scripts/clean.sh

