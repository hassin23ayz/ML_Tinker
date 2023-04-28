Create a separate folder

~$ export ML_PATH="$HOME/ml"
~$ mkdir -p $ML_PATH
~$ pip3 --version
~$ pip3 install --upgrade pip
~$ pip3 install --user --upgrade virtualenv

~$ cd $ML_PATH
~/ml$ virtualenv env
~/ml$ source env/bin/activate

(env)~/ml$ pip3 --version
(env)~/ml$ pip3 install --upgrade pip
(env)~/ml$ python3 --version
(env)~/ml$ python3 -c "import jupyter, matpotlib, numpy, pandas, scipy, sklearn"

(env)~/ml$ jupyter notebook


