
This is a repo for Jupyter by Matt Harrison.

# Start Docker

See https://hub.docker.com/r/jupyter/datascience-notebook/

Build Image

    $ docker build -t py-ml-clus .
    
Run Image

    $ docker run -it --rm -p 9999:8888 -t py-ml-clus
    
Connect to Image with brower http://localhsot:9999

     
