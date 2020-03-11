# Installation with a virtual environment 

It is recommended to use `virtualenv` to create a separate Python environment where we can install packages freely, without affecting your system's modules.



Install `virtualenv`

```
$ pip install virtualenv
```

Create a virtual environment

```
$ virtualenv -p python3 py3venv
```

In the example above we are creating a virtual environment with Python 3 called py3venv in the current working directory.

To use the newly created virtual environment, we need to activate

```
$ source py3venv/bin/activate
```



Once in the virtual environment you can install Python modules with pip as 

```
$ pip install numpy notebook matplotlib pandas seaborn
```

To check if the modules were correctly installed you can import the them in Python or Ipython. For example, for NumPy

```python
import numpy
```

if you don't get errors it means you're all set.

