# zth
Zero to hero

Following along with [Andrej Karpathy's](https://karpathy.ai/)[Neural Network: Zero to Hero course](https://karpathy.ai/zero-to-hero.html).

## Setup

```powershell
# init
uv init

# virtualenv
uv venv
.\venv\Scripts\activate

# add
uv add graphviz ipykernel jupyterlab matplotlib numpy

# requirements.txt
uv pip compile pyproject.toml -o requirements.txt --emit-index-url

# install graphviz
winget install graphviz

# update path
[Environment]::SetEnvironmentVariable("PATH", ($env:PATH + ";C:\Program Files\Graphviz\bin"), "User")
```