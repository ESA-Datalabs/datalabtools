# Saving notebook cell output when tab is closed
While executing code in a jupyter notebook, celloutput is directly displayed inline. While a task can run on Datalabs without the user being connected, the current jupyter limitations make it difficult to save the cell output of the execution.
To circumvent missing output, this output can be saved beforehand:
At the beginning of the cell, which output should be saved one can append:

```bash

%%capture my_output_var
#... code to be executed

```
and then after code completion the cell's output can be viewed with:

```bash

my_output_var.show()

```

[The corresponding Stackoverflow page](https://stackoverflow/a/57664588)