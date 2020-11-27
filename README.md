Kaggle ['Microsoft Malware Classification Challenge'](https://www.kaggle.com/c/malware-classification) 3rd place solution
=======
### Mikhail Trofimov, Dmitry Ulyanov, Stanislav Semenov.

Gets score 0.0040 on private leaderboard

How to reproduce submission
=======
Don't forget to check paths in ./src/set_up.py!
```
./create_dirs.sh
cd ./src
./main.sh
cd ../
```
and run all the code in 
`learning-main-model.ipynb`,
`learning-4gr-only.ipynb`,
`semi-supervised-trick.ipynb` and 
`final-submission-builder.ipynb`.

Dependencies
=======
* python 2.7.9
* ipython 3.1.0
* sklearn 0.16.1
* numpy 1.9.2
* pandas 0.16.0
* hickle 1.1.1
* pypy 2.5.1 (with installed joblib 0.8.4)
* scipy 0.15.1
* xgboost-0.3 

Hardware
=======
We run this code on machine with 16 cores and 120 GB RAM.
The most memory-consuming part is processing 4-gramms. All the others will require no more than 32 GB RAM.
