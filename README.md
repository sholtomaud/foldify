# foldify

The run.txt file is a batch file which will install the following packages to an OSX environment:

1. Nodejs Version Manager - used for managing different versions of the Node.js runtime
2. The latest stable version of nodejs to get the npx facility from npm
3. The basictex package for OSX - enables latex 
4. A number of latex packages (calculator circuitikz setspace amsmath mathtools amssymb booktabs tabularx bondgraphs pgfplots bm listings multirow graphicx tikz textcomp color adjustbox collectbox)
5. A number of packages for Atom.io ( wordcount compare-files file-icons format-shell jscad-viewer minimap multi-paste zotero-picker jupyter-notebook )

# How to run

To run this package navigate to a terminal window and run the following at the command prompt

```bash

> bash <(curl -s https://raw.githubusercontent.com/shotlom/foldify/master/run.txt)

```

