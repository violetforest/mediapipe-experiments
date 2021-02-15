# mediapipe-experiments

Various experiments with [mediapipe](https://github.com/google/mediapipe), specified as Jupyer [notebooks](./notebooks). Small testing datasets are available in the [data/](./data) directory.

## Development

Requires [python>=3.8](https://github.com/pyenv/pyenv#installation) and [Node.js](https://nodejs.org/en/). 

With python 3.x installed, create a virtual environment for this project and activate it.

```shell
$ python -m venv venv
$ . ./venv/bin/activate
```

Then, install the project dependencies:

```shell
$ pip install -r requirements.txt
$ . ./venv/bin/activate
$ jupyter labextension install jupyterlab-plotly@4.14.3
```

And finally, start up Jupyter lab:

```shell
$ jupyter lab
```
