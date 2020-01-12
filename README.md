# Documentation Repository

This repository contains the `LaTeX` report as well as the slides we'll use during the class presentation. In order to compile the `LaTeX` document correctly you must navigate to the `LaTeX_report` folder and run:

```bash
pdflatex --shell-escape SVM_applied_to_DoS_detection.tex && bibtex SVM_applied_to_DoS_detection.aux && pdflatex --shell-escape SVM_applied_to_DoS_detection.tex && pdflatex --shell-escape SVM_applied_to_DoS_detection.tex
```
All these runs are needed to get the cross-references and the like updated. It just works :panda_face: