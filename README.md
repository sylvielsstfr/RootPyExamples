# RootPyExamples
This a a test to use Rootpy histogramming package for LSST and DESC-LSST

# in my configuration script I add three lines
MySetUp.sh
export ROOTSYS="/usr/local/root/pro"
source $ROOTSYS/bin/thisroot.sh
export PATH=${HOME}/.local/bin${PATH:+:$PATH}

# in my python installation, (version 2.7), I install ROOTPY as follow
rootpy
pip install --user rootpy

#I follow the instructions at
http://www.rootpy.org

