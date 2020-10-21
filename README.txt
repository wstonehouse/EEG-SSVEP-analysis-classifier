Welcome!

The following notebook is merely my process of self learning SSVEP anlysis.
I rewrote the whole thing to flow more like a tutorial. You can download the data
by just copying the dataset folder in SSVEP.

This notebook uses pipelines from MOABB. Instead of your standard import,
you must clone their repo and execute the following commands:

pip install -r requirements.txt
python setup.py develop    # because no stable release yet

The repo can be found at:
https://github.com/NeuroTechX/moabb

MOABB requires the following libraries:
mne numpy scipy scikit-learn matplotlib seaborn pandas pyriemann h5py

Best,
Will