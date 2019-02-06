# Jupyter image

Run like this:
```
docker run -p 8888:8888 -it --name rdkit_jupyter -v $HOME/jupyter_notebooks:/notebooks:Z informaticsmatters/jupyter-rdkit /bin/bash -c "jupyter notebook --notebook-dir=/notebooks --ip=0.0.0.0 --allow-root"
```
