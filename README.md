# Handwriting recognition model
Deep learning model which can recognize handwriting texts by several criteria

# Setting up project

1. Create python virtual environment
  
```bash
python -m venv {venv-name}
```

2. Activate venv

```bash
. {venv-name}/Scripts/activate
```

3. Install jupyter lab / notebook (inside venv)

```bash
pip install jupyterlab
```

4. Insatll ipykernel (inside venv)

```bash
pip install ipykernel
```

5. Create kernel from venv

```bash
python -m ipykernel install --name={venv-name}
```

6. Run jupyter

```bash
jupyter-lab
```
or
```bash
jupyter notebook
```

> **Warning**
> 
> **Do not forget to select installed kernel inside of jupyter lab / notebook**

7. (Remove kernel if necessary)

```bash
jupyter kernelspec uninstall {venv-name}
```
