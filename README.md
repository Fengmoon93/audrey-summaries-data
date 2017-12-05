# Master Thesis report data
In this repositories, I will put the summaries and related video which comes from Master Thesis.

## Summaries

In this repository are placed all the experiment done during Master Thesis. They will be organized for DeepTesla experiment and CARLA experiment.

Currently, Tensorboard summaries available are:
  * CV - [DeepTesla](https://github.com/lexfridman/deeptesla) with related video
  * NVIDIA - [DeepTesla](https://github.com/lexfridman/deeptesla) with related video
  * CNN LSTM - [DeepTesla](https://github.com/lexfridman/deeptesla) with related video
  * CNN LSTM - [CARLA data](https://github.com/carla-simulator/carla)
  * A3C - [CARLA data](https://github.com/carla-simulator/carla)
  
### Install Tensorboard
I assume you have Python3 installed.

First of all, install [Tensorflow](https://www.tensorflow.org/install/). For this thesis, it has been used Tensorflow 1.3.

Open a terminal and type:

```
$ sudo pip3 install tensorboard
```

### Show data

Once `pip3` has finished to install, open a terminal and type
```
$ cd <experiment-folder>

$ tensorboard --logdir=<summary_folder>/
```

## Experiment video

### DeepTesla

It will be loaded only video which contains data that are not used in training phase. If you would like to see training data, there are in the graph section plots which contains differences between neural network output and original output.


### CARLA

It will be loaded videos and related graphs from the original work.
