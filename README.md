# RWOP
My slides and jupyter notebook for my random walk on physics talk on neural networks. To get them:

  - You can download as zip from github
  - Using the command line: ````git clone https://github.com/lsgos/RWOP````
  
To run and view the ipython notebook (ipynb) file requires [jupyter](http://jupyter.org/): you can get this by
  - using pip: ````pip install jupyter````
  - Installing [anaconda](https://www.continuum.io/downloads), which will come with jupyter.
  
Once you have jupyter installed, open a terminal/command prompt, navigate to the directory where you downloaded this repository and run
````jupyter notebook````
to start the notebook interface. 

In order to run all the code in the notebook itself, you're going to need to install some extra python libraries /programs:
- [scipy](https://www.scipy.org/)
- [numpy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/)
- [caffe](http://caffe.berkeleyvision.org/)

Note that caffe is a huge pain to install, and I'm not totally sure it works at all on windows.
There is a community macOS port though I think. If you are having trouble then there is some help [here](https://www.ubuntu.com/desktop)


In case you are just looking for my last slide and don't want to/can't manage to install all of this stuff, here's my 'further reading' list from the talk.
- [Neural networks and deep learning][1]: An online book that derives backpropagation from scratch and shows how to implement a neural net totally 'by hand' in numpy
- [The unreasonable effectiveness of recurrent neural networks][2]: A fantastic blog post on recurrent nets (which are very cool indeed) and some crazy stuff thats been done with them
- [Atari][9] A neural network plays atari!
- [Grabber Farm][10]: Robots learning to pick stuff up
- [Colah's Blog][3]: Whole series of posts about deep learning and neural nets, including some more mathematical treatment of data as manifolds.
- [Tensorflow][4]: An open-source neural net library, which has some great hands on tutorials.
- [Caffe][5]: Another one, more tailored for image recognition, which comes with pre-trained models. **WARNING: CAFFE IS A NIGHTMARE TO INSTALL**
- [Torch][6]: Yet another neural net library, with the quirk of being in lua.
- [Scikit-Learn][7]: Easy machine learning in python, has a nice set of tutorials too.
- [Fork this talk on github][8]: This entire presentation is a jupyter notebook, and I plan to make the source avaliable on my github page, so you can see and run all the code I used to generate this slideshow! 


[1]: http://neuralnetworksanddeeplearning.com/
[2]: http://karpathy.github.io/2015/05/21/rnn-effectiveness/
[3]: http://colah.github.io/
[4]: https://www.tensorflow.org/
[5]: http://caffe.berkeleyvision.org/
[6]: http://torch.ch/
[7]: http://scikit-learn.org/
[8]: https://github.com/lsgos
[9]: https://www.youtube.com/watch?v=V1eYniJ0Rnk
[10]: https://research.googleblog.com/2016/03/deep-learning-for-robots-learning-from.html
