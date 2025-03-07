### Objectives
* Install a supported version of Python (compatible with Google Cloud).
* Use venv to isolate dependencies.
* Install an editor (optional).
* Install the Google Cloud CLI (optional).
* Install the Cloud Client Libraries for Python (optional).
* Install other useful tools.


install [python](https://cloud.google.com/python/docs/setup#installing_python)
* To use homebrew to install Python packages, you need a compiler, which you can get by installing Xcode's command-line tools.

```bash
xcode-select --install
```

```bash
brew install pyenv
pyenv install 3.9
#PYTHON_VERSION

#to verify
python3 --version
```

* To verify that pip3
  
```bash
pip3 --version
```

```bash
python -m pip install --upgrade pip
```

### Using venv to isolate [dependencies](https://cloud.google.com/python/docs/setup#installing_and_using_virtualenv)

```bash
cd my-project
python -m venv env

# Set your shell to use the venv paths for Python by activating the virtual environment:
source env/bin/activate

# Now you can install packages without affecting other projects or your global Python installation:
pip install google-cloud-storage

# pip install google-cloud-storage
deactivate
```