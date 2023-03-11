# Choosing the python version
My advise to choose python version is always a stable version. THough a nighly build will have better features, it takes some time for other participating softwares to come up with compatible components.
Fof this set up purpose. I am going to use python 3.11.2 (stable version). This step probably is the easiest of all

Go to https://www.python.org/downloads/
CLick on Download python 3.11.2 which should be right in front of you
It will download an exe.
Once the download is complete, Double Click and go through the installation process. All the default option you can let it be.
  
Once its installed, go to RUN/cmd and open a command prompt
# In the command prompt type python. You should see something like this below

Python 3.11.2.  (default, May 18 2021, 14:42:02) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32

Warning:
This Python interpreter is in a conda environment, but the environment has
not been activated.  Libraries may fail to load.  To activate this environment
please see https://conda.io/activation

Type "help", "copyright", "credits" or "license" for more information.
>>>

Usually tis means your python is set up. However there are some other default libraries that you should install such as
numpy, pandas etc
come out of the >>> prompt by typing exit() and pressing enter key

Type the following command
pip install numpy
and wait. it will install numpy locally for all users/or profile depending on your access previledges 
Then type the following command and press enter.
pip install pandas
This will install pandas. 
  
# Now practically you are all set for writing code. 
  I also told you that we will use use jupyter notebook for writing code. 

  For the the same, please write the following command and press enter
  pip install notebook
  After its installed to check whether its installed or not do the following
  
  in cmd prompt, type the following and press enter
  jupyter notebook
  
 Ideally it should pop open a borwser window with http://localhost:8888/tree url. This is a directory tree, you can choose your folder and create new ipython Notebook (ipynb) type file to write code from here.
 
This completes your python set up for all practical purposes. While doing programming, you might need other packages to add. But that would be simple. Once you figure out the name and version use the following command
pip install package_name=VERSION

Thank you, See you in KAFKA Set up
