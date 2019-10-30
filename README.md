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
virtualenv --python={PATH_TO_PYTHON_3.6.3}/python3.6 venv
```
#### 2. Make the Virtual Environment Active
##### 2.1 Windows
```sh
\venv\Scripts\activate.bat
```
##### 2.2 Linux
```sh
source venv/bin/activate
```
#### 3. Install this packages in specific versions
```sh
pip install -r requeriments.txt
```

#### 4. Running Application

First running all the [MNIST](MNIST.ipynb) file with Jupyter Notebook.
```sh
jupyter notebook
```

After that, close the jupyter notebook and run the commands:

##### 4.1 Windows
```sh
set FLASK_APP=srv.py && cd digits_classifier && flask run
```

##### 4.2 Linux
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


