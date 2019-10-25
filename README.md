# Image Classifier

This project utilizes the potential of machine learning to learn numerical patterns through drawing numbers on images to reproduce an Image Sorter. Machine learning was done through an IPython file, interpreted by a [Notebook Jupyter](https://jupyter.org/), and the UI application was created using the [Flask Framework](https://palletsprojects.com/p/flask/).

## Getting Started
### Prerequisites

* [Python - Version 3.6.3](https://www.python.org/downloads/release/python-363/) - It can be the major version of python or a minor version. You can easily mantain multiple versions from python with [Pyenv](https://github.com/pyenv/pyenv) library.

### Installing

#### 1. Create a Virtual environment with the python version 3.6.3 into the project path
##### 1.1 Windows
```sh
virtualenv --python={PATH_TO_PYTHON_3.6.3}/python.exe venv
```
##### 1.2 Linux
```sh
virtualenv --python={PATH_TO_PYTHON_3.6.3}/python3.6 
```
#### 2. Make the Virtual Environment Active
##### 2.1 Windows
```sh
source venv/Scripts/activate
```
##### 2.2 Linux
```sh
source venv/bin/activate
```
#### 3. Install this packages in specific versions
```sh
pip install numpy==1.17.0 
pip install scipy==1.0.0
pip install scikit-image==0.14.2
pip install scikit-learn==0.19.1
```
#### 4. Install this packages normally
```sh
pip install matplotlib
pip install jupyterlab
pip install flask
pip install wget
```

#### 5. Running Application

First running all the [MNIST](MNIST.ipynb) file with Jupyter Notebook.
```sh
jupyter notebook
```

After that, close the jupyter notebook and run the commands:

```sh
export FLASK_APP=srv.py && cd digits_classifier && flask run
```

### Recomendations

Use the [Pycharm IDE](https://www.jetbrains.com/pycharm/) to manage your apps.

If you have an access from Intel AI Dev Cloud and want run this application on your virtual machine, only install the
wget package and run all blocks from [MNIST](MNIST.ipynb) file. After that, copy all path from your local machine,
make all the steps bellow.

## Contributing

Please create a new [issue](https://github.com/lucasrochagit/image-classifier/issues) to buf fixes or contributing with us.

## Authors

* **Eduardo Borba** - *Initial work* 
    * [Linkedin](https://www.linkedin.com/in/eduardo-queiroz-78aa83150/)
    * [Github](https://github.com/EduBrQ)
* **Lucas Rocha** - *Project Maintainer*
    * [Linkedin](https://www.linkedin.com/in/lucasrochacc/)
    

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE) file for details


