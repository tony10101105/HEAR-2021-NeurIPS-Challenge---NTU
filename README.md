# HEAR-2021-NeurIPS-Challenge---NTU

## Description

We concatenate the embeddings generated from the three models below.
```
1. Wav2Vec2 (without fusion)
2. Crepe (without fusion)
```

## Installation of the package

```shell
pip install \
git+https://github.com/tony10101105/HEAR-2021-NeurIPS-Challenge---NTU.git@cat_wav2vec2_crepe
```

## Usage

```python3
# In python code:
from GURA import cat_wav2vec2_crepe
```
## CUDA Version

* CUDA: 11.4

## Package Version

* torch==1.9.1+cu111
* transformers==4.11.3
