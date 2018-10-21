# RooFitBasics
Repo for a RooFit basics tutorial

This repo contains the file `RooFit_Basics.ipynb` which can be opened in a ROOT notebook by launching `root --notebook` inside the directory and selecting the ipynb. 

If you experience problems with the ROOT notebook, make sure the python version you are using matches the one in the kernel. This can be found (e.g) under ` ~/.rootnb/kernels/root/kernel.json`. For example, mine looks like 

```
{
 "language": "c++",
 "display_name": "ROOT C++",
 "argv": [
  "/System/Library/Frameworks/Python.framework/Versions/2.7/bin/python2.7",
  "-m",
  "JupyROOT.kernel.rootkernel",
  "-f",
  "{connection_file}"
 ]
}
``` 
