# __Tensorflow__
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img src="https://pbs.twimg.com/profile_images/1103339571977248768/FtFnqC38_400x400.png" height='100' width='100'>


### __Hello World in TensorFlow__
``` python

import tensorflow as tf
import numpy as np
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Dense

model = Sequential([Dense(units=1, input_shape=[1])])
model.compile(optimizer='sgd', loss='mean_squared_error')

xs = np.array([-1.0, 0.0, 1.0, 2.0, 3.0, 4.0], dtype=float)
ys = np.array([-3.0, -1.0, 1.0, 3.0, 5.0, 7.0], dtype=float)

model.fit(xs, ys, epochs=500)
print(model.predict([10.0]))
```


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
