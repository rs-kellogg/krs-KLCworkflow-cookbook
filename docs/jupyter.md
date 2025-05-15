# Jupyter Notebooks 📓

[VS Code Juypyter Notebooks](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)

![VS Code](./images/vscode-jupyter.png)

## Runing a notebook:

1. Create or open a Jupyter Notebook file (with a `.ipynb` extension) in VS Code.
2. Use the command palette (Ctrl+Shift+P) and type "Python: Select Interpreter" to choose the Python environment you want to use (note: the Python environment must have the `ipykernel` package installed).
3. Set the kernel to the desired Python environment by clicking on the kernel picker in the top right corner of the notebook editor.


```{admonition} Exercise
:class: dropdown
Let's create our own notebook and run it.

1. Create a new Jupyter Notebook file in VS Code and set the kernel.
2. Add Markdown cells with a title and description.
3. Add a code cell to read in a CSV file and display the first few rows.
4. Run the code cells and observe the output.
5. Save the notebook and export it to a Python script.
```


```{admonition} Example Code
:class: dropdown
```python
import pandas as pd
df = pd.read_csv("data.csv")
print(df)
```
