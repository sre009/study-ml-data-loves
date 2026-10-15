# study-ml-data-loves


uv python install 3.14
uv venv --python 3.14

source .venv/bin/activate
python3 --version   # 3.14.8
python --version    # 3.14.8
which python        # .../study-ml-data-loves/.venv/bin/python

uv venv lesson1 --python 3.14
source lesson1/bin/activate

uv run python --version
uv run python script.py

uv venv --python 3.14
source .venv/bin/activate
uv pip install jupyterlab pandas matplotlib ipykernel
echo ".venv/" >> .gitignore
jupyter lab