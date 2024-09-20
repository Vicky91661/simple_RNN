# Environment Setup
### Use this command to make environment

    conda create -p venv python==3.10.14 -y
### Use this command to activate environment
    conda activate venv/

# Installation of all the packages written on requiremnts.txt

    pip install  -r requirements.txt
# Install ipykernel
    pip install ipykernel
    
# Using pip in an environment

To use pip in your environment, in your Terminal window or an Anaconda Prompt, run:

    conda install -n myenv pip

As of now, TensorFlow does not officially support Python 3.12. The latest supported Python versions for TensorFlow are typically Python 3.9 or Python 3.10. TensorFlow might not work properly with Python 3.12, as TensorFlow releases often lag behind new Python releases.