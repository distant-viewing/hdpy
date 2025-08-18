These are the main commands to control Quarto within the book:

```sh
source .venv/bin/activate

quarto preview
quarto clean
quarto render
```

To run the examples, do the following:

```sh
source .venv/bin/activate

quarto render notebook01a.qmd --to html
```
