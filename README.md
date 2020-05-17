# Plant Pathology Kaggle (2020)

Link to competition: https://www.kaggle.com/c/plant-pathology-2020-fgvc7

Obtained a score of 0.958/1, currently ranked in the top half of the leaderboard.
(17 May 2020)

### By Craioveanu Sergiu-Ionut

## Prerequisites

* Google Colab/IPython Notebook
* PyTorch
* Fast.ai
* Google Drive
* GPU/TPU (Optional, but highly recommended)

To make sure versions match, run these starting instructions (similar to the ones found in the notebook)

```bash
!pip uninstall torch -y
!pip uninstall torchvision -y
!pip install torch==1.4.0 torchvision==0.5.0

!curl -s https://course.fast.ai/setup/colab | bash
```

## Kaggle Setup

```python
!pip install --upgrade --force-reinstall --no-deps kaggle

# set kaggle json dir
import os
#Personal example
os.environ['KAGGLE_CONFIG_DIR'] = "/content/drive/My \Drive/fastai-v3/.kaggle/"
os.environ['KAGGLE_USERNAME'] = "thesergiu"
os.environ['KAGGLE_KEY'] = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"

```

## Download and unzip Kaggle data
```python
kaggle competitions download -c plant-pathology-2020-fgvc7

#unzip the data
!unzip plant-pathology-2020-fgvc7
```

## Inspect Notebook For More Details
