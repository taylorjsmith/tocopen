# Theory of Computing: An Open Introduction

![Header image of the book cover art](/images/header.png)

## Summary
*Theory of Computing: An Open Introduction* is a book suitable for courses on 
the theory of computing at both the undergraduate and graduate levels, and 
for self-study. Topics are introduced in a logical order: we begin with the 
simple finite automaton and progressively introduce stronger models of 
computation, up to the Turing machine. We then shift from the models 
themselves to what the models can compute, which opens up a discussion on 
computability and decidability. This leads us to a journey through complexity 
theory. The remainder of the book focuses on a selection of special topics.

This book was written by [Taylor J. Smith](http://taylorjsmith.xyz), an 
assistant professor in the [Department of Computer Science](https://www.stfx.ca/department/computer-science) 
at [St. Francis Xavier University](https://www.stfx.ca/).

The book is currently in its &alpha; pre-publication edition (September 2024).

## Getting Started
To compile the book on your computer, you must first install [a LaTeX distribution](https://www.latex-project.org). 
Then, either from your terminal or from your chosen editing software, typeset 
the file `book.tex`. All chapters and sections will be automatically imported.

The `book.tex` file uses the `pdflatexmk` engine to typeset the book. You 
should not need to run individual commands separately; everything will be 
taken care of in one run.

Individual chapter and section files can be found in the `chapters` folder. 
Appendices can be found in the separate `appendices` folder. The `images` 
folder contains graphics and figures.

In the preamble of the `book.tex` file, you will find four flags:
* `\styletrue` is a special flag for my use. (See the note below.)
* `\drafttrue` overlays a draft watermark on each page and adds page backreferences to the bibliography.
* `\printtrue` removes link colouring and makes other changes specific to my style file.
* `\printmarkstrue` makes changes specific to my style file.

*Note.* You will see that your typeset version of the book does not look like 
the version of the book found on my website. This is because I have chosen to 
keep the style files for my version of the book proprietary. Of course, form 
does not affect function: all of the book's contents are included in this 
repository.

## License
This book is published under a [Creative Commons BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/). 
You are free to use and adapt the material in this book under the conditions 
that you provide an attribution to the source material and that you distribute 
any adapted material under the same Creative Commons BY-SA 4.0 license terms.

If you use or adapt the material from this book, please include the following 
attribution:

> Taylor J. Smith. *Theory of Computing: An Open Introduction*. Self-published open educational resource, &alpha; pre-publication edition, 2024. [taylorjsmith.xyz/tocopen/](http://taylorjsmith.xyz/tocopen/).

## Your Feedback
If you would like to share your feedback with me (e.g., to correct an error, 
to suggest something you would like to see in a future edition, or just to 
send me a nice note), please *do not* open an issue or submit a pull request 
to this repository. Instead, please contact me via email.
