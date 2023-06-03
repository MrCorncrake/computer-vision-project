# computer-vision-project
Project for Computer Vision

## Download data from
https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8/data

## How to create venv
```
python -m venv ./venv/
```
### Activate venv with:

*For Windows Power Shell:*
```
.\venv\Scripts\Activate.ps1
```

*For Linux Shell:*
```
source ./venv/bin/activate
```

### Download requirements.txt
*Ensure you activated the venv beforehand!*
```
pip install -r requirements.txt
```

### Create jupyter kernel
```
python -m ipykernel install --user --name jupyter-ucz-gleb-kernel
```

### GPU support on windows
```
tensorflow 2.12 doesn't support GPU in native Windows, instructions for https://www.tensorflow.org/install/pip?hl=pl#windows-wsl2 
have to be followed. Or you can use a lower tensorflow version (max 2.10).
```