# Write A Data Science Blog Post
## [Udacity - Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

See the insights in this blog:

- [Aircraft Accident - Should You Be Afraid?](https://medium.com/@ha.tranxuan.hn/aircraft-accident-should-you-be-afraid-6832244a280)

Read analysis in [`workspace/eda.html`](workspace/eda.html)

### Overview

This project study the aviation accident dataset, with the motivation
of what affects the likelihood of an aircraft accidents.

### How to run

1. Create and activate Conda environment:

  ```shell
  conda env create -f environment.yml
  source activate ud-dsnd
  ```

2. Open the notebook:

  ```shell
  jupyter notebook
  ```

  Open `eda.ipynb` to view the project.

### Project structure

- `data/`: contain `.zip` file of analyzed data. The project use the
[Aviation Accident Database & Synopses](https://www.kaggle.com/khsamaha/aviation-accident-database-synopses)
from [Kaggle](https://www.kaggle.com)
- `workspace`: Analysis work

### Libraries

- numpy
- pandas
- matplotlib
- scikit-learn
