<link href="/Users/wanghu/phenomenon/personal/markdown/kevinburke.css" rel="stylesheet"></link>


## Getting the dependencies

### For Linux

    sudo apt-get install build-essential python-dev python-numpy python-setuptools python-scipy libatlas-dev libatlas3-base

**Note** In order to build the documentation and run the example code contains in this documentation you will need matplotlib:

    sudo apt-get install python-matplotlib

\# _The steps below were tested under Mac OS X._

#### Easy install

    pip install -U scikit-learn

or:

    easy_install -U scikit-learn



#### To test if it work:

Testing requires having the _nose_ library. After installation, the package can be tested by executing from outside the source directory:


    sudo easy_install nose
    nosetests sklearn --exe
