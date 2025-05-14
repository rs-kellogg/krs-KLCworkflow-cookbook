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

1. Create a new Jupyter Notebook file in VS Code and set the kernel to your chosen Python environment.
2. Add Markdown cells with a title and description.
3. Use the Generate Code button to generate code snippets
4. Run the code cells and observe the output.
5. Save the notebook and export it to a Python script.
6. Open the exported Python script and review the code.
7. Make any necessary modifications to the code in the Python script.
8. Run the modified Python script in VS Code to see the results.
9. BONUS: run the script on all KLC nodes in parallel.
```


```{admonition} Example Code
:class: dropdown
```python
def timer(n_seconds):
    for i in range(0, n_seconds):
        print(f".", end="")
        time.sleep(1)
    print("Time's up!")
```
