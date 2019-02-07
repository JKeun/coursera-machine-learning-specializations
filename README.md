## Install Graphlab in Python environment using virtualenv

### Install pyenv 2.7.10 version
- [python build issue](https://github.com/python-pillow/Pillow/issues/1753#issuecomment-193874588)
- [pyenv build issue](https://github.com/pyenv/pyenv/wiki/Common-build-problems#error-the-python-ssl-extension-was-not-compiled-missing-the-openssl-lib)
```
CFLAGS="-I$(brew --prefix openssl)/include" \
LDFLAGS="-L$(brew --prefix openssl)/lib" \
PYTHON_CONFIGURE_OPTS="--enable-unicode=ucs2" \
pyenv install 2.7.10
```

### Create and activate a new virtual environment
```
# Create a virtual envrionment (named ml-2.7)
pyenv virtualenv 2.7.10 ml-2.7

# Activate virtualenv
pyenv activate ml-2.7
```

### Ensure pip version >= 7
```
# Make sure pip is up to date
pip install --upgrade pip
```

### Install GraphLab Create
```
# Install you licensed copy of GraphLab Create
pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/[your registered email address here]/[your product key here]/GraphLab-Create-License.tar.gz
```
