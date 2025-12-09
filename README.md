# zth
Zero to hero

Following along with [Andrej Karpathy's Neural Network Zero to Hero Lectures](https://karpathy.ai/zero-to-hero.html).

## Setup

```bash
# init
uv init

# virtualenv
uv venv
.\venv\Scripts\activate

# add
uv add jupyterlab

# kernel
python -m ipykernel install --name=zth --user

# requirements.txt
uv pip compile pyproject.toml -o requirements.txt --emit-index-url
```