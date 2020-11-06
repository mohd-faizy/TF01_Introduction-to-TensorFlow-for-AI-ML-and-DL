# __Tensorflow__

<img src="https://pbs.twimg.com/profile_images/1103339571977248768/FtFnqC38_400x400.png" height='100' width='100'>

TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.

TensorFlow was originally developed by researchers and engineers working on the Google Brain team within Google's Machine Intelligence Research organization to conduct machine learning and deep neural networks research. The system is general enough to be applicable in a wide variety of other domains, as well.

### __Why Tensorflow?__

- __Easy model building:__
Build and train ML models easily using intuitive high-level APIs like Keras with eager execution, which makes for immediate model iteration and easy debugging.

- __Robust ML production anywhere:__
Easily train and deploy models in the cloud, on-prem, in the browser, or on-device no matter what language you use.

- __Powerful experimentation for research:__
A simple and flexible architecture to take new ideas from concept to code, to state-of-the-art models, and to publication faster.

### __“Hello World” of machine learning__
``` python

import tensorflow as tf
import numpy as np
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Dense

l0 = Dense(units=1, input_shape=[1])
model = Sequential([l0])
model.compile(optimizer='sgd', loss='mean_squared_error')

xs = np.array([-1.0, 0.0, 1.0, 2.0, 3.0, 4.0], dtype=float)
ys = np.array([-3.0, -1.0, 1.0, 3.0, 5.0, 7.0], dtype=float)

model.fit(xs, ys, epochs=500)

print(model.predict([10.0]))
print("Here is what I learned: {}".format(l0.get_weights()))
```

The output was as follows:
```
Here is what I learned: [array([[1.9967953]], dtype=float32),
array([-0.9900647], dtype=float32)]
```
Thus, the learned relationship between X and Y was Y = 1.9967953X – 0.9900647


---

<img src="https://github.com/mohd-faizy/__TensorFlow_Developer__/blob/master/Tensorflow_Dev_png/01.png">

|__Course 1: Introduction to TensorFlow for AI, ML and DL__                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [01 Housing Prices ](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/01_Housing_Prices.ipynb)                                                         |
| [02 Computer Vision fashion MNIST](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/02_Computer__Vision_fashion_MNIST.ipynb)                           |
| [03 Callbacks](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/03_callbacks.ipynb)                                                                    |
| [04 Handwriting Recognition](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/04_Handwriting_Recognition.ipynb)                                        |
| [05 Improving The CV Accuracy Using Convolution](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/05_Improving_The_CV_Accuracy_Using_Convolution.ipynb)|
| [06 Experiment with filters and pools](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/06_Experiment_with_filters_and_pools.ipynb)                    |
| [07 Improve_MNIST_with_convolutions](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/06_Experiment_with_filters_and_pools.ipynb)                      |
| [08 Horse Or human Classifier](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/08_Horse_Or_human_Classifier.ipynb)                                    |
| [09 Classifier Happy Or Sad Images](https://github.com/mohd-faizy/TensorFlow_Developer_AI_ML_DL/blob/master/09_Classifier_Happy_Or_Sad_Images.ipynb)                          |

- Connect with me:


[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][StackExchange AI]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/faizy-mohd-836573122/
[StackExchange AI]: https://ai.stackexchange.com/users/36737/cypher


---


![Faizy's github stats](https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mohd-faizy&layout=compact)](https://github.com/mohd-faizy/github-readme-stats)
