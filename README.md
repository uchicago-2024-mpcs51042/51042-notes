# 51042 Notes Repository

## How to use this Repo

I will push notes to this repository throughout the quarter.
If you are keeping your own notes in this repository you should generally keep them in separate files to avoid accidental git conflicts.

Either make companion files in each directory, or keep your notes in a separate directory/notebook altogether.

I will create a notebook for each topic, numbered in the order they're introduced.

### Jupyter Notebooks

There are a few ways to look at these notes:

1. You can browse these on GitHub.com in a non-interactive form.

2. If you open them in VS Code it will prompt you to install an extension for Jupyter notebooks, doing so will let you use them from VS Code.

3. If you install Jupyter locally, you have a few options for working with `.ipynb` notebooks:

- `uv run jupyter lab` - the newer UI, will start a server and 
- `uv run jupyter notebook` - the older UI, perfectly functional still
- VS Code will open these in it's own editor

If you run one of the `uv run` options, you'll need to navigate to the .ipynb file in the window that opens in your browser.

**Note:** To stop a server, press `Ctrl-C` and then 'y' to the prompt.
