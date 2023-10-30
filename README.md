## Running the notebook

In order to be fully reproducible, the notebook requires dependencies to be installed and a virtual environment to be created and activated before running the .ipynb file locally. This can be done using poetry.

* Install the dependencies
```bash
poetry install
```
* Activate the virtual environment created by poetry
```bash
source $(poetry env info -p)/bin/activate
```
* Run the notebook
```bash
jupyter notebook ./airbnb_athens_analysis/assignment.ipynb
```