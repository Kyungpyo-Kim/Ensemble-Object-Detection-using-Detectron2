# Ensemble-Object-Detection-using-Detectron2
Ensemble Object Detection Algorithm using Detectron2


## Getting Started
1. Environments
    * OS: Ubuntu20.04
    * CUDA: 11.3
    * Pytorch==1.10
    * Detectron2==0.6

2. Installation
    ```bash
    sudo apt-get install -y python3-dev python3-venv
    python3 -m venv env
    source env/bin/activate
    python -m pip install pip -U
    python -m pip install -r requirements.txt
    python -m ipykernel install --user --name env --display-name ensemble_detectron2
    python -m pip install "git+https://github.com/facebookresearch/detectron2@v0.6"
    ```

3. Run (reproduce results)
    * open "detectron2_ensemble.ipynb" and run all cells
    * if you don't have GPU, you can utilize results json files without GPU running.
    * [Google Colab](https://colab.research.google.com/drive/1lQQzE4ELRo6Dh47AaH27vmKe0Nomiu8t?usp=sharing )


## Reference
* [Detectron2](https://github.com/facebookresearch/detectron2)
* [Detectron2 Install](https://detectron2.readthedocs.io/en/latest/tutorials/install.html)
* [COCO Dataset](https://cocodataset.org)
* [Weighted Boxes Fusion](https://arxiv.org/pdf/1910.13302.pdf)