# deep-dream-demo


## Before attending the workshop:
- Clone git repository: `$ git clone https://github.com/flacout/deep-dream-demo.git`
- Pull the docker image (it takes a while to download):
```
docker run -d -v /$(pwd)/:/home/jovyan/work \
           -p 8888:8888 gaarv/jupyter-keras start-notebook.sh --NotebookApp.token=''
```
- Choose a few picture you would like to modify, to experiment with the algorithm.
- Optionaly you can read some articles to get familiar with the topics:

https://medium.com/@samuellynnevans/first-weeks-of-andrew-ng-beginners-steps-for-gradient-descent-and-the-cost-function-in-univariate-a2016a6f6258

https://medium.com/@tifa2up/image-classification-using-deep-neural-networks-a-beginner-friendly-approach-using-tensorflow-94b0a090ccd4

## Run the environment (tensorflow, keras, jupyter-notebook):

1. git clone the repository `$ git clone https://github.com/flacout/deep-dream-demo.git`
2. enter the repository `$ cd deep-dream-demo`
3. Run a docker image with python3, tensorflow, keras, and jupyter-notebook installed:

```
docker run -d -v /$(pwd)/:/home/jovyan/work \
           -p 8888:8888 gaarv/jupyter-keras start-notebook.sh --NotebookApp.token=''
```


4. Go to localhost:8888 in a browser.
5. Enter the directory `work`, you should see the current directory of your local machine.
6. Open the DeepDream.ipynb file.


## References

The code is from the book "Deep Learning with Python" from Francois Chollet, 
the code from the book can be found here: https://github.com/fchollet/deep-learning-with-python-notebooks

The docker image comes from gaarv: https://hub.docker.com/r/gaarv/jupyter-keras/

Thanks to both of them!!