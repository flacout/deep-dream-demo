# deep-dream-demo

1. Run a docker image with python3, tensorflow, keras, and jupyter-notebook installed:

docker run -d -v /$(pwd)/:/home/jovyan/work \
           -p 8888:8888 gaarv/jupyter-keras start-notebook.sh --NotebookApp.token=''


2. Go to localhost:8888 in a browser
3. git clone the fabrice/deepDream repository in your current working directory
4. In jupyter-notebook open the DeepDream.ipynb file