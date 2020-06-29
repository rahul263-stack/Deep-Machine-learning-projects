
## Real World Problem
This case-study focuses on generating music automatically using Recurrent Neural Network(RNN). 
We do not necessarily have to be a music expert in order to generate music. Even a non expert can generate a decent quality music using RNN.
We all like to listen interesting music and if there is some way to generate music automatically, particularly decent quality music then it's a big leap in the world of music industry.
__Task__: Our task here is to take some existing music data then train a model using this existing data. The model has to learn the patterns in music that we humans enjoy. Once it learns this, the model should be able to generate __new___ music for us. It __cannot simply copy-paste__ from the training data. It has to understand the patterns of music to generate new music. We here are not expecting our model to generate new music which is of professional quality, but we want it to generate a __decent quality music__ which should be __melodious__ and __good to hear__.
Now, what is music? In short music is nothing but a __sequence of musical notes__. Our __input__ to the model is a sequence of musical events/notes. Our __output__ will be new sequence of musical events/notes. In this case-study we have limited our self to single instrument music as this is our first cut model. In future, we will extend this to multiple instrument music. 
## Data Source:
1. http://abc.sourceforge.net/NMD/
2. http://trillian.mit.edu/~jc/music/book/oneills/1850/X/

__From first data-source, we have downloaded first two files:__
* Jigs (340 tunes)
* Hornpipes (65 tunes)
## How to Run the Model
In order to run the model you can run the file " Music_Generation_Train2.ipynb"
You can also load weights which are in the file" Data2/Model_Weights/". There are total 9 weight files over there. Each weight file represents the epoch number. For instance " Weights_50.h5" are the weights saved at epoch 50. We ran our model for total of 90 epochs. 
You can add more layers into your model and fine tune the existing layers in the model. Any epoch weight can be loaded for fine tuning or "Transfer Learning".
## How to Generate Music Sequence
Once the model is defined and weights are calculated then run "Generate_Music.ipynb" file. If the architecture of your model is different than just change the architecture of the model in "make_model" function and generate music sequence.
## Type of Data:
There are total of 405 music tunes in abc notation.
## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
3. keras
## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/
3. Keras: pip install keras
## Built With
* ipython-notebook - Python Text Editor
* numpy, scipy- number python library
* pandas - data handling library
* Keras - Deep Learning Library
## Authors
*Rahul Kuamr - Complete work  
## References
* https://www.appliedaicourse.com/
* https://folkrnn.org/
* https://en.wikipedia.org/wiki/ABC_notation
* https://abcjs.net/abcjs-editor.html
* https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
* http://karpathy.github.io/2015/05/21/rnn-effectiveness/
* https://medium.com/artists-and-machine-intelligence/neural-nets-for-generating-music-f46dffac21c0
