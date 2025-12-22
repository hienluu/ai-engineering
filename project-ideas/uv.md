## This files contains basic information about workng with UV

### pin a Python version for uv to use
uv python install "version"


### creating a new project  [documentation](https://docs.astral.sh/uv/concepts/projects/init/)
uv init --python 3.xx

### create a project. It will create a folder w/ the provided name
uv init <name>

### create a virtual environment
uv venv

uv venv <name>

### create and activate a new environment with specific python version
uv venv --python <version>

### activate an env
source .venv/bin/activate

.venv/Scripts/activate


### add dependecies using pip
uv pip install <package>

### add dependecies from requirements.txt
uv add -r requirements.txt

### add package
uv add <package name>

### capture the dependencies into the requirements.txt
uv pip freeze > requirements.txt 

### run python in an environment
uv run <python file>

uv run python <python file>


