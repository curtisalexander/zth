# zth
Zero to hero

Following along with [Andrej Karpathy's](https://karpathy.ai/)[Neural Network: Zero to Hero course](https://karpathy.ai/zero-to-hero.html).

## Setup

```bash
# init
uv init

# virtualenv
uv venv
.\venv\Scripts\activate

# add
uv add ipykernel
uv add jupyterlab

# kernel
python -m ipykernel install --name=zth --user

# requirements.txt
uv pip compile pyproject.toml -o requirements.txt --emit-index-url
```