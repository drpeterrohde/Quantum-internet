Quantum Internet
================

LaTeX, Mathematica, Illustrator, PDF and image repository for our Quantum Internet book.

## LaTeX
LaTeX is a typesetting solution. Proper docs: [https://www.latex-project.org/help](https://www.latex-project.org/help/)

Useful commands:

### Clean compiled files/dirs

    latexmk -C

### Build new PDF

    latexmk -pdf

## git
git is a distributed version control system (DVCS). Proper docs: [https://git-scm.com/doc](https://git-scm.com/doc)

Useful commands:

### Make a change, commit and push it up to Github

    touch foo.tex                     # <- a random change
    git commit -am 'Changed <>'       # Commits your change(s)
    git push -u origin <branch_name>  # Replace with actual branch name

### New branch
Best to run this before commiting any changes, to simplify things:

    git checkout -b new_branch_name

### Merge changes; and obsolete old branch

    git merge -s <branch_to_keep> <obsoleted_branch>
