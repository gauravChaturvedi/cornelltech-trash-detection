# cornelltech-trash-detection

## Installation

```
	pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.0.0-py2-none-any.whl

	pip install --upgrade virtualenv

	Your targetDirectory will be given by which python

	virtualenv --system-site-packages <targetDirectory>

	virtualenv --system-site-packages ~/tensorflow

	source ~/tensorflow/bin/activate

	Test if Tensorflow is correctly installed by doing the following:

	$ python

	Enter the following short program inside the python interactive shell:

		# Python
		import tensorflow as tf
		hello = tf.constant('Hello, TensorFlow!')
		sess = tf.Session()
		print(sess.run(hello))

	If the system outputs the following, then you are ready to begin writing TensorFlow programs:

		Hello, TensorFlow!

	Otherwise, use the following - Install [Tensorflow](https://www.tensorflow.org/install/)

	If Tensorflow is running correctly, then clone this repo

	and finally:

	python classify.py
```

<br/>

## Usage

### Classify objects

```javascript
python classify.py
```

This program will take a picture using your webcam and then try to classify it as plastic, paper, metal, cardboard, glass or trash