# Get your environment fixed

## Create a virtual env
```sh
$ python3 -m venv venv
```
## Activate your env
```sh
$ source venv/bin/activate
```

## Add the venv path as Kernel
```sh
$ pip3 install --user ipykernel
$ python3 -m ipykernel install --user --name=venv
```
## Install python libraries
```sh
$ pip3 install keras tensorflow scikit-learn pandas numpy Theano
$ pip3 install torch-tensorrt -f https://github.com/pytorch/TensorRT/releases
```

## Remove the venv kernel
```sh
$ jupyter kernelspec list
$ jupyter kernelspec uninstall myenv
```
