# Topic classifier

## Setup 

1) Download BERT model [here](https://drive.google.com/open?id=1R7m5aw21PuM_QWKBLUY3QtLTVxTNLykP) and Tensorflow model [here](https://drive.google.com/open?id=1Toq0muNqJcTHYPF-z0yrYYb1TFKqx6ee)

2) Decompress model files in ROOTDIR: `tar -xvf tf_model.tar.gz; tar -xvf bert_model.tar.gz` 

3) In a conda environment or otherwise: `pip install -r requirements.txt`

4) Download bert_dp helper functions: `python -m deeppavlov install squad_bert`

5) To run on test set: `python run_interactively.py` 

## Results 
Final results on validation set can be found [here](https://docs.google.com/spreadsheets/d/1aarAx_o73rIkrEc6mWywOvjacPc0V99avKeLF_re5h4/edit#gid=0)
