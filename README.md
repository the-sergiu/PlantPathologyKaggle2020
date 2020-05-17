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

## Links to other Valuable Notebooks
Leaderboard

Username                        Error rate    Link to notebook
1. @vitsalis                    0.024725  https://github.com/vitsalis/kaggle/blob/master/FGVC7/solution.ipynb
1. @darthwaydr007               0.024725  https://github.com/darthwaydr007/kaggle/blob/master/Plant_pathology_updated1.ipynb
2. @TheSergiu                    0.046703 https://github.com/thesergiu/PlantPathologyKaggle2020/blob/master/PlantPathologyKaggle2020.ipynb
3. @Abdullah        0.060440      https://github.com/abdnafees/fastai-lesson2-hw/blob/master/fastai_lesson2_apple_diseases.ipynb
4. @perceptronnn                0.065934      https://github.com/anurag25/shared_notebooks/blob/master/plant_pathology_1.ipynb
5. @Marcos Pereira              0.104396      https://github.com/marcospgp/kaggle-plant-pathology-2020/blob/master/apple_diseases.ipynb
6. @Oliver Klingefjord          0.107143      https://github.com/Klingefjord/course-v3/blob/master/apple_diseases.ipynb
