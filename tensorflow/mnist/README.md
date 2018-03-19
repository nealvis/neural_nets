# A trained network for the mnist dataset.

This network is based on the [TensorFlow 1.4 mnist_deep.py example.](https://github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/examples/tutorials/mnist/mnist_deep.py)  It was modified, trained, and saved in accordance with the [NCSDK TensorFlow Guidance page ](https://movidius.github.io/ncsdk/tf_compile_guidance.html) so that it can be compiled with the NCSDK compiler.

The Tensorflow trained network compatibile with the Intel Neural Compute SDK is in the following files:
- mnist_inference.data-00000-of-00001
- mnist_inference.index
- mnist_inference.meta

The NCSDK graph file built with NCSDK 1.12 compiler is in this file:
- mnist_inference.graph
