## Introduction  
- 최대 반응금액 찾기

## Model
- XGBoost 사용
- 

## Installation
- Python 3.9 가상환경 사용

### Virtual Environment
```
conda create -n project_name python==3.9
```

### Prerequisites  
- Numpy : `pip install numpy`  
- Pandas : `pip install pandas`
- Matplotlib : `pip install matplotlib`
- librosa : `conda install -c conda-forge librosa`
- torchaudio : `pip install torchaudio==0.8.0`
- tqdm : `pip install tqdm`
- hydra : `pip install hydra-core --upgrade`
- flask : `pip install flask`
- flask_restx : `pip install flask_restx`
- python-docx : `pip install python-docx`

### Install from source
```
pip install -r requirements_backend.txt
```

### Start Server
```
python start_server.py
```
