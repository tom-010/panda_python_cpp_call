Call C++ from Python Showcase
=============================

I want to call a C++-Function from my python code. 

This repoistory shows the problem. There is the `main.py`which is the
copy&paste onboarding example from the Panda3D-Website. 
It contains a `addPanda()'-Method which adds the panda to the scene. 

The goal is to do this via C++. Therefore there also exists the 
`main.cc` which is the same program written in C++ (also from the 
onboarding tutorial). It contains the method `addPanda()`.

Going back to the python version `main.py` there is the method 
`addPandaViaCpp()` in this method I want to call the C++ `addPanda()`.

Now I sould be able to remove line 18 in `main.py` and uncomment line 16 
and there should be no difference in the result (panda is still there).