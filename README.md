# Setup
1. Follow the `pyenv` installation directions at https://github.com/pyenv/pyenv
2. Run `$ pyenv install 3.5.3`
3. Run `$ pyenv exec pyvenv env`
4. Activate the development environment: `$ source env/bin/activate`
5. Run `$ pip install -r requirements.txt`

# Verify Installation
Open a terminal and activate the environment (step 4). Run `$ python` and then try to import keras `>>> import keras`. You should see the message "Using TensorFlow backend."

# Examples
Dogs vs. Cats: `$ python examples/dogs_v_cats.py --dataset [training_data_path]`
- Tutorial from: http://www.pyimagesearch.com/2016/09/26/a-simple-neural-network-with-python-and-keras/
- https://www.kaggle.com/c/dogs-vs-cats/data
