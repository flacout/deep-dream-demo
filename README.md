# deep-dream-demo


## Run the environment (tensorflow, keras, jupyter-notebook):

1. Run a docker image with python3, tensorflow, keras, and jupyter-notebook installed:

docker run -d -v /$(pwd)/:/home/jovyan/work \
           -p 8888:8888 gaarv/jupyter-keras start-notebook.sh --NotebookApp.token=''


2. Go to localhost:8888 in a browser
3. git clone the https://github.com/flacout/deep-dream-demo.git repository in your current working directory
4. In jupyter-notebook open the DeepDream.ipynb file


## References

The code is from the book "Deep Learning with Python" from Francois Chollet, 
the code from the book is  here: https://github.com/fchollet/deep-learning-with-python-notebooks

The docker image comes from gaarv: https://hub.docker.com/r/gaarv/jupyter-keras/

Thanks to both of them!!