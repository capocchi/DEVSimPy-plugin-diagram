# What is DEVSimPy-plugin-diagram
It is a plugin for DEVSimPy which give the PDEVS abstract simulator three from master model.

#Depends
* [python-profiler](https://pypi.python.org/pypi/psutil)
* [networkx](https://networkx.github.io/)

for windows user: [matplotlib](http://sourceforge.net/projects/matplotlib/files/) and networkx

#Installation
In order to view the diagram plugin in the DEVSimPy plugin manager (Options->Preferences->Plugins), just:
* add the diagram.py  files into the "plugins" directory of DEVSimPy 
* add the string "diagram" to the \__all\__ variable of the plugins/\__init\__.py file 

#Use
It appear when user want simulate a model by clicking on the "Ok" button in the simulation dialogue. The three depends on the simulation strategy chosen by the user. 
