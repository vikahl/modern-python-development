# Modern Pythonutveckling / Modern Python development

This repository contains the slides for my presentation originally presented
at [Omegapoints conference OpKoKo 19.2][1].

The slides has since then been translated to English and can thus be found
both in Swedish and in English.

Note that the Swedish and English versions does not match exactly, adaptations
was made to suit the audience where the talk was presented.

The _git_ icon in the presentation refers to a specific tag/commit in the
todo-extractor repository. The todo extractor and the project template that
was mentioned in the talk can be found at:

- [todo-extractor](https://github.com/vikahl/todo-extractor)
- [python-template](https://github.com/vikahl/python-template)

## Introduction

### Swedish

    Python är populärare än någonsin och har under de senaste åren fått stora
    förbättringar inte bara i språket utan i verktygskedjan. Vi går igenom
    hela flödet från installation av Python till att ett färdigt paket ska
    publiceras på PyPi och ser samtidigt hur nya verktyg och metoder har gjort
    processen enkel och smidig.

### English

    Python is more popular than ever and during the last years there has been
    large improvements in the tooling around the language. This presentation
    will go through tooling that ease the development and show how to take a
    simple script to a maintainable package that can be published on PyPi.

## Typesetting

The presentation is written in Latex can be typeset preferably with Luatex.

Pygments is needed (`pipx install pygments`) for the code examples to work and
lualatex needs to be run with `--shell-escape` comand. As always with Latex 
you will probably need to run the command multiple times for everything to 
align.

```shell
$ lulatex --shell-escape presentation
```


[1]: https://www.opkoko.omegapoint.se/
