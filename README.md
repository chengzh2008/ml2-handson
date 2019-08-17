### Setup python env

```
 cd ml2-handson
 python3 -m pip --version
 python3 -m pip install --user -U pip
 python3 -m pip install --user -U virtualenv
 vi ~/.zshrc
 source ~/.zshrc
 virtualenv my_env
 source my_env/bin/activate
 python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
 python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
 pip install jupyter
 ipython3 kernelspec install-self
 jupyter notebook
```
