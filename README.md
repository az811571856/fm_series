# fm_series

### Abstruct
Use tensorflow to write fm / ffm / deepfm / (comming soon)...

### structure:
- lib/fm.py -> fm model written by python normal
- lib/tensorflow_fm.py -> fm model written by tensorflow
- lib/tensorflow_ffm.py -> ffm model written by tensorflow
- lib/tensorflow_deepfm.py -> deepfm model written by tensorflow
- lib/tensorflow_wide_and_deep.py -> wide_and_deep written by tensorflow(keras)

- notebookfile/fm_fit_func_and_classification.ipynb -> run fm.py
- notebookfile/tensorflow_fm.ipynb -> run tensorflow_fm.py
- notebookfile/tensorflow_ffm.ipynb -> run tensorflow_ffm.py
- notebookfile/tensorflow_deepfm.ipynb -> run tensorflow_deepfm.py
- notebookfile/tensorflow_wide_and_deep.ipynb -> run tensorflow_wide_and_deep.py


### How to run

- `cd fm_series`
- `pipenv install`
- `pipenv run jupyter lab --no-browser`
- In pycharm 
    - Click `Run`
    - Type url and then the notebook file can run.


