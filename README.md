# install python 3.6
yum install gcc bzip2-devel libffi-devel openssl-devel 
./configure --enable-optimizations 
make altinstall      # make altinstall is used to prevent replacing the default python binary file /usr/bin/python

- install pandas:
pip3.6 install pandas
