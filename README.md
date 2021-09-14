# React in Python

This shows you how to use React 16+ inside Python, using [pyodide](https://pyodide.org). The example shows how to update a very simple button using React hooks with only Python code. The only JS code needed is to interface JS with the Python code (thanks to Pyodide).

I recommend checking out `pyodide` if you are interested in running the pydata stack inside your browser via webassembly. Note that this is not a Py > JS transpiler - python, numpy, pandas etc. are really running inside your browser. This also allows you to import Python libraries from `pip` via `micropip` (see pyodide docs).

My tweet expands on this: https://twitter.com/xhluu/status/1420814963459960836

## Inspiration

The original notebooks that tried to use React inside iodide (the predecessor to pyodide):
* https://alpha.iodide.io/notebooks/362/
* https://alpha.iodide.io/notebooks/420/
