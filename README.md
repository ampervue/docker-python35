
A Docker image running Ubuntu:trusty with latest Python 3.5 (built from source)
This is the base image for:

    - https://github.com/ampervue/docker-ffmpeg
    
    - https://github.com/ampervue/docker-python34-ffmpeg
    
    - https://github.com/ampervue/docker-python34-opencv


### To Build

~~~~
docker build -t <imageName> .
~~~~

### To pull and run from hub.docker.com

Docker Hub: https://registry.hub.docker.com/u/dkarchmervue/python34/

Source and example: https://github.com/ampervue/docker-python34

~~~~
docker pull dkarchmervue/python34
docker run --rm -ti dkarchmervue/python34 python --version
docker run --rm -ti -v ${PWD}:/work dkarchmervue/python34 python your-python-script.py
docker run --rm -ti dkarchmervue/python34 bash
~~~~

## Python 2.7

For Python 2.7, use https://github.com/ampervue/docker-python27
