# md2ipynb #

_md2ipynb_ converts markdown files to _IPython notebooks_. It's a hackish
solution, but I hate it that I can't edit an IPython notebook in my favorite
editor easily. This script will take code blocks that look like

    ~~~ {.python}
    ...
    ~~~


And wrap them in an IPython code cell. All other parts are wrapped in markdown
cells.


To create an **ipynb** just type:

    ./md2ipynb myfile.md myfile.ipynb



