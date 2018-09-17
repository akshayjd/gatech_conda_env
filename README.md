#What is this
This repository has collection of Anaconda and pip environment files for different courses offered at Georgia Tech.

#How to install Anaconda environment
```conda create --name [env_name] --file conda_env.txt``` change [env_name] to a name you like.

#How to install PIP environment
Activate previously installed conda environment by using ```source activate [env_name]```. if you are using windows, use ```activate [env_name]``` instead. Once the conda environment is activated, use
```pip install -r requirements.txt``` to install dependencies.
