Karung
======

An example of creating mapreduce programs in Python by using Hadoop and Pig 

To checkout my presentation click [here](http://nbviewer.ipython.org/urls/raw.github.com/agconti/Karung/master/Karung.ipynb).

###Installation
On Windows.
Get and install [Virtual Box](https://www.virtualbox.org/).
Get the [Cloudera Quick Start VM](https://ccp.cloudera.com/display/SUPPORT/Cloudera+QuickStart+VM). This contains Hadoop, Pig, Hive, HBase, and Zookeeper installed on RedHat Linux. 
Start your VM and go to the terminal. Execute the following commands in root to install Python2.7:
```
yum groupinstall "Development tools"
yum install zlib-devel bzip2-devel openssl-devel ncurses-devel sqlite-devel readline-devel tk-devel

wget http://python.org/ftp/python/2.7.5/Python-2.7.5.tar.bz2
tar xf Python-2.7.5.tar.bz2
cd Python-2.7.5
./configure 
make && make altinstall
```

Enter the following commands to install distribute:
```
wget http://pypi.python.org/packages/source/d/distribute/distribute-0.6.45.tar.gz
tar xf distribute-0.6435.tar.gz
cd distribute-0.6.45
python2.7 setup.py install
```
A good tutrial on the process is located [here](http://toomuchdata.com/2012/06/25/how-to-install-python-2-7-3-on-centos-6-2/).

###Name Etymology 
The Karung Snake is a slang term for the Elephant Trunk Snake. Because these projects will focus on interacting with Hadoop with python, it seemed like a good choice.
