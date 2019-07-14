# LaTeX based resume template
## Usage
This document can be compiled in 2 languages (en/nl). To switch the preferred language simply change `\entrue or \nltrue` on line 72 to the desired language.
## Compile instructions
This can only be compiled with `XeLaTeX` because of some fonts used in the template.
It also needs custom fonts which can be found in [this repository](https://github.com/robbedec/resume/tree/master/fonts).

The package Layaureo really wants a4paper apposed to letterpaper, we have to set a flag to keep compiling through warnings. This can be achieved by commenting the thrown error in `layaureo.sty`.

Create document on Linux/MacOS
```
xelatex -interaction=nonstopmode robbe-decorte-resume.tex
```
Or windows
```
xelatex.exe -interaction=nonstopmode robbe-decorte-resume.tex
```

## Example
A preview of this template can be found [here](https://robbedec.github.io/resume/).

## Credits
This template is provided by Illya Starikov, more information can be found on his [blog](https://freneticarray.com/about/).
