# Running Keras

### Running the Docker Image for CPU only

To run tensorflow on CPU, simply use the Docker command:

```docker run -it -p 8888:8888 `pwd`:/notebooks/src/ tensorflow/tensorflow```

In a jupyter notebook, run `!pip install keras cython h5py`, and you're set up!

### Running the Docker Image on GPU

Make sure nvidia-docker is installed on your instance or computer with CUDA-enabeled GPU. The best way to do is to use an nvidia-docker AMI on AWS on an instance of type p2 (GPU compute).

Once you've got this up and running, you can just use the following command:

```nvidia-docker run -it -p 8888:8888 -v `pwd`:/notebooks/src/ tensorflow/tensorflow:latest-gpu```

Just like before, you can run `!pip install keras cython h5py` in a jupyter notebook and you're set up!