# Presentation tools

## Spell check with vim

`:setlocal spell spelllang=fr,en`

Correct word: *z=*

Add word to dictionary: *zg*

## Generate pdf slides from markdown

**requires latex and pandoc >= 2.0**

`pandoc -t beamer --highlight-style zenburn --pdf-engine=xelatex -V theme:metropolis -o slides.pdf slides.md`

