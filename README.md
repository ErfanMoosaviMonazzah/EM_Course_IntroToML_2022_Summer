# EM_Course_IntroToML_2022_Summer

## Displaying Multiple output in vscode jupyter notebooks
### One time solution
__Copy and Paste the following code into one of the cells, run the cell__
```
from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = "all"
```

### Permanent solution
Go to the following path:
```
C:\Users\your_profile\\.ipython\profile_default
```
Create a file named ```ipython_config.py```
Copy and paste the following code into that file:
```
c = get_config()

c.InteractiveShell.ast_node_interactivity = "all"
```
