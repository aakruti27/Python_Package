# Python_Package
This is the first ever python package that I created. 


We created classes and used various concepts of OOPs, such as inheritance and modulation. 


Magic methods are used to perform operations on two objects of same class, say addition of two distributions. 


What else I learnt was the fact that "_ _inti_ _ .py" file is necessary, otherwise you can't make a package. That's why in disributions package, we first added the init file and then created and coded classes for Binomial, Gaussian and General Distrivution according to the mathematical formulas. 
init file is there so that whenever the package is used, the first thing that the computer will do is execute init, and hence it'll be importing the right classes.


Once done with the main coding part, we next need to terminal and from the location of these files, next we can install our package by "pip install ." (cd __location of your package__  and then pip install .)  

Once installed, you can exit or open new terminal and use your package/ Binomial class there like so: 
1. start python: __"python"
2. import: __"from distributions import Binomial"
3. create object: __"Binomial_obj= Binomial(.4, 20) 
