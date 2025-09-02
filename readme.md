# Run twice to get all references correct
```
pdflatex main
makeindex main.nlo -s nomencl.ist -o main.nls
pdflatex main
```