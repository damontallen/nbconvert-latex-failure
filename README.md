This git page was created to investigate why 

    ipython nbconvert "Latex_test.ipynb" --to latex --post PDF

failes to generate a valid latex version of the rendered latex.

[Static Latex_test.ipynb](http://nbviewer.ipython.org/urls/github.com/damontallen/nbconvert-latex-failure/raw/master/Latex_test.ipynb)

##Solution:

The solution turned out to be using " ${}$ " instead of just " $ $ " to make a blank line appear in a LaTex document.

[The problem was solved by Jakob on stackoverflow.](http://stackoverflow.com/questions/18722000/using-nbconvert-to-make-a-pdf)
