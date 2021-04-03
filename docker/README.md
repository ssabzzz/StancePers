# Reproduce Experiments Using Docker
</br>

Docker is <a href="https://github.com/googlecolab/colabtools/issues/299 ">not supported in Colab</a>, So this dockerfile sets up an environment which you could reproduce our experiments on a personal computer with a <strong>CPU</strong>. If you have a cuda-capable GPU, probably need a few extra configuration steps which can be found on <a href="https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html">nvidia website</a>.

## Getting Started

Build from the root folder of the repository.
Run:
  ```sh
docker build -t stancepers .
  ```
This builds an image from the dockerfile that you need to run using:
  ```sh
docker run -p 8888:8888 stancepers
  ```
Make sure that port `8888` on your host machine is not already allocated. The command above will start a JupyterLab enviroment in which you can run the notebooks.
## Caution
Start with a small `BATCH_SIZE` to make sure it won't eat up all of your RAM space.


