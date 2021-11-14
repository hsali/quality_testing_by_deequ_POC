# POC for pyqdeequ with offline and online mode.

* deequ-test1.ipynb for online auto maven based 
* deequ-test2.ipynb for offline jar based



## tested with python=3.9
## environment setup 

* conda create -n de2 python=2.7
* conda activae de2
* pip download pydeeque -d wheels  # online mode
* pip install --no-index --find-links=wheels pydeequ # offline mode
* pyspark --jars "comma seperated list of jars"

## environment setup 
### download packages to specific folder

pip download pydeequ -d wheels


### install packages from wheel 

pip install --no-index find-links=wheels pydeequ

