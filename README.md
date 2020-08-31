# A Singularity container running ijavascript nootbook

* Running IJavaScript (Jupyter) Nootbook (http://n-riesco.github.io/ijavascript/)
* Based on an official Python docker image (python:3.7-alpine)
* Small footprint (The image (SIF) size is about 160MB)

To invoke a server with the default port 8888:

    singularity run shub://okuisatoshi/singularity-ijavascript

Or you may want to specify a port number explicitely:

    IJS_PORT=8889 singularity run shub://okuisatoshi/singularity-ijavascript

You are required to enter a token shown when the server is starting up at the first time.
 
