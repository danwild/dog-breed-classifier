# dog-breed-classifier
Deep learning exercise with pytorch to identify dog breeds from a picture


## Setup notes
Uses [Deep Learning AMI (Ubuntu) v23](https://aws.amazon.com/marketplace/pp/B077GCH38C) 

```
# enter provided env
source activate pytorch_p36

# quick setup jupyter
jupyter notebook --generate-config
sed -ie "s/#c.NotebookApp.ip = 'localhost'/#c.NotebookApp.ip = '*'/g" ~/.jupyter/jupyter_notebook_config.py
jupyter notebook --ip=0.0.0.0 --no-browser

# navigate to url provided (will need to replace IP)
# may also need to select kernal corresponding to env above
```
