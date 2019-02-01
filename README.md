# BEX.AI-Machine-Learning-Course

An introductory machine learning course based on [Andrew Ng's Machine Learning Course](https://www.coursera.org/learn/machine-learning)
Initially taught @ DB BEX

## Setup for labs
- Download & install latest [Anaconda for Python 3](https://www.anaconda.com/distribution/#download-section)
- Fire up a command line & `cd` to the root folder of this project
- ``conda create -n bexai pip python=3.7``
- ``activate bexai``
- ``pip install ipython ipykernel matplotlib pandas jupyter scikit-learn seaborn pipupgrade``
- ``python -m ipykernel install --name bexai``
- Now you're ready to go, fire up ``jupyter notebook`` and open the `ipynb` file of the lab (remember to also choose the `bexai` kernel, if it's not selected by default)