## import notion notes into obsidian

markdown format,

some things are returned as csv, such as kanbans and anything in database view format

We will keep most things as markdown tables if they are not kanbans

transform kanban csv → kanban obisidian md format (kanban extension)

transform normal data csv → md table format

keep links to existing pages inside data csvs

## installation

Needs python, recommended virtualenv,

pip install requirements.txt

## usage

Currently code is very unstable and in development,

1. make sure to output your notion workspace content as Markdown and CSV format
2. unzip your export and rename the folder to Export/
3. Place it root directory and run python notebook notion-export.ipynb to output Transformed files to Transformed/
