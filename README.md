# Human Parsing with Self-Correction

A tool for segmenting human parts in images using deep learning.

## Install
```
conda env create -f environment.yaml
conda activate schp
pip install -r requirements.txt
```

## Train
```
python train.py
```

## Evaluate
```
python evaluate.py --model-restore [CHECKPOINT_PATH]
```

## License
MIT License