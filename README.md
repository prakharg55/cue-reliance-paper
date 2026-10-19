# Ask the Model: Counterfactual Cue Reliance Predicts Worst-Group Failure and Targets Repair

Prakhar Gupta, Terry Jingchen Zhang, Florent Draye, Bernhard Schölkopf, Zhijing Jin

This repository has the LaTeX source of the paper, and [`main.pdf`](main.pdf) is the
compiled version. The code, the logs of every trained model and the analysis scripts
are in [prakharg55/cue_reliance](https://github.com/prakharg55/cue_reliance).

## Building

```bash
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

The ACL style files `acl.sty` and `acl_natbib.bst` are included.
