# Music generator using ML


# Overview
## Use TensorFlow to generate short sequences of music with a [Restricted Boltzmann Machine](http://deeplearning4j.org/restrictedboltzmannmachine.html). 

# Dependencies

* Tensorflow
* pandas
* numpy
* msgpack
* glob
* tqdm 

Missing dependencies can be downloaded using pip

# Getting started

To train the model and create short clips, just install all the dependencies and clone this directory and run 

`python rbm_chords.py`

In the terminal, then 
type

`python merge_samples.py`

To merge all clips into a final one. Then play the final.mid to enjoy the music usingan appropriate player.
