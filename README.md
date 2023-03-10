# TeethSeg
## Install
```shell
conda create -n toothseg python=3.10
conda activate toothseg
```

```shell
pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
```
```shell
pip install -r requirements.txt
```

## Folder
```shell
|- dataset
    |- tooth
        |- cindydata
            |- image
            |- label
            |- data.json (use exp.ipynb -> Preprocess cell)
|- TeethSeg
```
