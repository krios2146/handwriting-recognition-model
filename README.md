# Handwriting recognition model
Deep learning model which can recognize handwriting texts by several criteria

# Setting-up jupyter kernel

1. Create python virtual environment
  
```bash
python -m venv {venv-name}
```

2. Activate venv

```bash
. {venv-name}/Scripts/activate
```

3. Insatll ipykernel

```bash
pip install ipykernel
```

4. Create kernel from venv

```bash
python -m ipykernel install --name={venv-name}
```

> **Warning**
> 
> **Do not forget to select installed kernel inside of jupyter lab / notebook**

5. (Remove if necessary)

```bash
jupyter kernelspec uninstall {venv-name}
```
