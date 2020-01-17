# A study of flight delays and weather

$ brew update
$ brew install pyenv
$ brew install pyenv-virtualenv


Next in your .zshrc, .bashrc, or .bash_profile (depending on which shell you use) add the following towards the bottom:

eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"

vim .bashrc 

Run source .bashrc

Then 

$ pyenv install 3.7.5
$ pyenv virtualenv 3.7.5 flight_data_3.7.5
$ pyenv activate flight_data_3.7.5
$ pip install -r requirements.txt

