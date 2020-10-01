### Introduction

Hands-on tutorial for machine learning

### Prerequisites

- Basic understanding of Machine Learning concepts
- Basic Python knowledge
- Basic Docker knowledge
- Docker installed
- Approx. 1GB free disk space

### Setup lab environment

Lab environment requires docker. To run the lab environment:

- clone this repo
- run docker

```console
git clone https://github.com/hpe-container-platform-community/machine-learning-intro-tutorial.git
cd machine-learning-intro-tutorial
docker run -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/base-notebook
```

Note that the container folder `/home/jovyan/work` maps to the current folder, `machine-learning-intro-tutorial`.

Inspect the output for the URL, e.g.

```console
...
[I 19:35:31.353 NotebookApp] Jupyter Notebook 6.1.4 is running at:
[I 19:35:31.353 NotebookApp] http://d8ce476914a2:8888/?token=d7c9f2df7c0f369dcdacc114cac6f8897e1e0987a1a5e275
[I 19:35:31.353 NotebookApp]  or http://127.0.0.1:8888/?token=d7c9f2df7c0f369dcdacc114cac6f8897e1e0987a1a5e275
```

Open the URL (for me this was: http://127.0.0.1:8888/?token=d7c9f2df7c0f369dcdacc114cac6f8897e1e0987a1a5e275)

**NOTE:** You will get a different URL every time you run the docker instance.




