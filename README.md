# Modern Pythonutveckling / Modern Python development

This repository contains the slides for my presentation _Modern Pythonutveckling_
 at [Omegapoints conference OpKoKo 19.2](https://www.opkoko.omegapoint.se/).

The slides and the rest of this repository is in Swedish.

The _git_ icon in the presentation refers to a specific tag/commit in the
 todo-extractor repository. The todo extractor and the project template that
 was mentioned in the talk can be found at:

- [todo-extractor](https://github.com/vikahl/todo-extractor)
- [python-template](https://github.com/vikahl/python-template)

## Introduction

    Python är populärare än någonsin och har under de senaste åren fått stora
     förbättringar inte bara i språket utan i verktygskedjan. Vi går igenom hela
     flödet från installation av Python till att ett färdigt paket ska publiceras
     på PyPi och ser samtidigt hur nya verktyg och metoder har gjort processen
     enkel och smidig.

## Typesetting

The presentation is written in Latex can be typeset preferably with Luatex.

Note that Pygments is needed (`pipx install pygments`) for the code examples to
 work and lualatex needs to be run with `--shell-escape` comand. As always with
 Latex you will probably need to run the command multiple times for everything
 to align.

```shell
$ lulatex --shell-escape presentation
```
