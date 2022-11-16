# ESN\_Classification\_LRP\_ENSO

This repository contains supplementary material for experiments with layer-wise relevance propagation (LRP) on Echo State Networks (ESNs) applied to some Earth system variability: El Nino Southern Oscillation (ENSO).

Preprint has been published, see: <https://arxiv.org/abs/2210.09958>

Final version can be found In Proceedings of the 3rd International Conference on Machine Learning Techniques (MLTEC 2022), Zurich, Switzerland, vol. 12, no. 20, pp. 115-130 (2022).

## Technical Environment

Python code has been developed using Docker containter with JupyterLab environment, Tensorflow and several extensions, based on jupyter/tensorflow-notebook.

To start a JupyterLab within this container, run shell:

```$ docker pull mlandthayen/py-da-tf:latest```
```$ docker run -p 8888:8888 --rm -it -v $PWD:/work -w /work mlandthayen/py-da-tf:latest jupyter lab --ip=0.0.0.0```

and open the URL starting on `http://127.0.0.1...`.
