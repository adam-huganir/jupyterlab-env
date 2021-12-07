# jupyterlab-env
A nice little jupyter-lab setup with SSLand other niceties

# To use
```bash
# Assuming you don't have a jupyter setup yet and poetry installed
git clone https://github.com/adam-huganir/jupyterlab-env.git ~/.jupyter
cd ~/.jupyter
poetry install
poetry run jupyter notebook password # set up a password
poetry run jupyter lab
```
You will need to define the following environmental variables
```
JUPYTERLAB_URL
JUPYTERLAB_SSL_CERT
JUPYTERLAB_SSL_KEY
```
