# Ensemble-Object-Detection-using-Detectron2
Ensemble Object Detection Algorithm using Detectron2

## Getting Started
```bash
sudo apt-get install python3-dev
python3 -m venv env
source env/bin/activate
python -m pip install pip -U
python -m pip install -r requirements.txt
python -m ipykernel install --user --name env --display-name ensemble_detectron2
python -m pip install "git+https://github.com/facebookresearch/detectron2@v0.6"
python -m jupyterlab
```

## Model Selection for Ensemble


## Environments
* OS: Windows11 
    * [install visual-cpp-build-tools](https://visualstudio.microsoft.com/ko/visual-cpp-build-tools/)
    * [enable long file path](https://windows789.com/ko/windows-11-10%EC%97%90%EC%84%9C-win32-%EA%B8%B4-%EA%B2%BD%EB%A1%9C%EB%A5%BC-%ED%99%9C%EC%84%B1%ED%99%94-%EB%98%90%EB%8A%94-%EB%B9%84%ED%99%9C%EC%84%B1%ED%99%94%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95)
* Python: 3.8
* CUDA: 11.3
* Pytorch==1.10
* Detectron2==0.6

## Reference
* [Detectron2](https://github.com/facebookresearch/detectron2)
* [Detectron2 Install](https://detectron2.readthedocs.io/en/latest/tutorials/install.html)
* [COCO Dataset](https://cocodataset.org)