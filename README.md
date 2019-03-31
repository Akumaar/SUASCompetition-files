# SUASCompetition-files

To install the AUVSI-SUAS module needed for accessing the interop API go through the following steps:

download/Clone this directory into your local machine and copy the files into your Python2.7/Site-Packages directory. The full path should be: /usr/local/lib/python2.7/site-packages. 

Next, go to the SUAS_Compeition directory and run the install.sh file. You can do this by executing the following command:

sh install.sh 

This will install the necessary dependencices for executing the SUAS_Competition code. 


To run the Client script, cd into the ```gcs``` directory, then run:

```
export FLASK_APP=flask_gcs.py
python -m flask run --with-threads
```

Ensure that the version of Python that you are using is 2.7.x. If you attempt to use Python 3, the program will crash with a timeout exception.





