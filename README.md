# Setup
1. Follow the `pyenv` installation directions at https://github.com/pyenv/pyenv
2. Run `$ pyenv install 3.5.3`
3. Run `$ pyenv exec pyvenv env`
4. Activate the development environment: `$ source env/bin/activate`
5. Run `$ pip install -r requirements.txt`

# Verify Installation
Open a terminal and activate the environment (step 4). Run `$ python` and then try to import keras `>>> import keras`. You should see the message "Using TensorFlow backend."
