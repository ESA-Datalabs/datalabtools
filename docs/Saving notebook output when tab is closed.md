# Saving notebook cell output when tab is closed
While executing code in a jupyter notebook, cell output is directly displayed inline. 
While a task can run on Datalabs without the user being connected, the current jupyter limitations make it difficult to save the cell output during the execution.
To circumvent missing output, this output can be saved by adding one line of code to each cell beforehand:
At the beginning of the cell, of which output should be saved one can append:

```py

%%capture my_output_var
#... code to be executed

```
and then after code completion the cell's output can be viewed with:

```py

my_output_var.show()

```

[The corresponding Stackoverflow page](https://stackoverflow/a/57664588)
