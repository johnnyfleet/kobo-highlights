# Kobo Highlights

This project is a quick and dirty way to extract annotations from Kobo reader with the help of [Kobuddy](https://github.com/karlicoss/kobuddy)

I normally use October but found the ordering of annotations infuriating to simplify my notes.

## Outputs
It extracts the annotations/highlights into:
- CSV file
- Single markdown file with all annotations grouped by book
- Individual markdown files, one for each book, in the book_annotations folder.

## Pre-requisites
- Install kobuddy (I just cloned)
- `./kobuddy annotations >> annotations.txt`
- put that annotations file into the root of this project
- Run the jupyter notebook
