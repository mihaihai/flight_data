# A study of flight delays from NY

<img src="http://www.airportspotting.com/wp-content/uploads/2015/05/NewYorkCityAirports.jpg" alt="The main 3 airports of New York city" width="400"/>
In this notebook, I study a database of over 330 000 flights that departed from New York in 2013 for 105 different destinations in the USA to figure out which factors influence delays and which not. I will try to make an informed decision as to whether one airport is better than the others.

This notebook is written by Mihai Munteanu in Python 3.7.

#### Clone the repository

Run 
``` 
$ git clone https://github.com/mihaihai/flight_data.git
$ cd flight_data
```
to clone the repository locally and enter the folder.

#### Set up the Python environment

The notebook is made to run on Python 3.7 with the requirements in `requirements.txt` so please set up and activate such an environment before running `jupyter notebook`. Below you can see one way to do using `pyenv` on MacOS.

Run the following commands to install `pyenv` and `pyenv-virtualenv`
```
$ brew update
$ brew install pyenv
$ brew install pyenv-virtualenv
```

Next, in your `.zshrc`, `.bashrc`, or `.bash_profile` (depending on which shell you use) add the following towards the bottom:

```
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

and then source the file you modified (e.g. `$ source .bashrc`), so that your terminal recognizes `pyenv`.


Finally to set up the environment run

- ```$ pyenv install 3.7.0``` to install the version of Python used in this notebook,
- ```$ pyenv virtualenv 3.7 flight_data_3.7``` to create a new environment using Python 3.7.5,
- ```$ pyenv activate flight_data_3.7``` to activate the environment,
- ```$ pip install -r requirements.txt``` to install the requirements.

Now you can run the Python3 server by typing `$ jupyter notebook` in your terminal. 

