# dog-breed-classifier
Deep learning exercise with pytorch to identify dog breeds from a picture


## Setup notes
Uses [Deep Learning AMI (Ubuntu) v23](https://aws.amazon.com/marketplace/pp/B077GCH38C) 

```
# enter provided env
source activate pytorch_p36
python -m pip install -r requirements.txt

# quick setup jupyter
jupyter notebook --generate-config
sed -ie "s/#c.NotebookApp.ip = 'localhost'/#c.NotebookApp.ip = '*'/g" ~/.jupyter/jupyter_notebook_config.py
jupyter notebook --ip=0.0.0.0 --no-browser

# navigate to url provided (will need to replace IP)
# may also need to select kernal corresponding to env above
```

## Images

Also need to download:
- [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
  - Goes in: `<project_root>/dogImages`
- [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
  - Goes in: `<project_root>/lfw`
