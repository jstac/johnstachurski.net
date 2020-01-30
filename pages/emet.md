---
title: A Primer in Econometric Theory
permalink: emet
menu_item: true
order: 5
---

**Random Quote:** _The goal of the scientist is to comprehend the
phenomena of the universe that he observes around him. To prove that he
understands he must be able to predict. To predict quantitatively one
must have a mechanism for producing numbers, and this necessarily
entails a mathematical model._ – Richard Bellman

---

# A Primer in Econometric Theory

This is the homepage for my graduate level econometric theory text,
published
[by MIT Press](https://mitpress.mit.edu/books/primer-econometric-theory).

## About

The following is from the preface to the book:

> This is a quick course on modern econometric and statistical theory, along
> with the underlying ideas from probability and linear algebra that
> budding econometricians should know. The focus is on foundations and general
> principles. Although it was written to teach from, there are many solved
> exercises, making the text well suited to self-study. Exercises, worked
> examples and sample code are used to reinforce ideas.

## Samples

- [Table of Contents](/pdfs/emet_samples/toc.pdf)
- [Chapter 1: Introduction](/pdfs/emet_samples/ch1.pdf)
- [Chapter 2: Vector Spaces](/pdfs/emet_samples/ch2.pdf)
- [Chapter 3: Linear Algebra and Matrices](/pdfs/emet_samples/ch3.pdf)
- [Chapter 8: Estimators](/pdfs/emet_samples/ch8.pdf)
- [Chapter 11: Regression](/pdfs/emet_samples/ch11.pdf)
- [Chapter 14: Regularization](/pdfs/emet_samples/ch14.pdf)

## Lecture Slides

Thanks to the work of
[Akshay Shanker](https://github.com/akshayshanker), a full set
of lectures slides are available – both PDF and source (TeX)

- Lecture 1 [PDF](/pdfs/Lecture_1.pdf)|
  [LaTeX](/downloads/Lecture_1.tex))
- All other PDFs and source files are available
  [from GitHub](https://github.com/jstac/econometric_theory_slides)

They are licensed under BSD-3 and you are free to modify them in any way
you wish.

## Source Code

The code in the book is written in a mixture of
[R](https://www.r-project.org/),
[Python](https://www.python.org/) and
[Julia](http://julialang.org/) and organized into
[Jupyter notebooks](https://jupyter.org/).

You can either

- run the notebooks live in your browser or

- download them and run them locally

Details follow.

### Run the Notebooks Live

This is good option for experimenting. You can run, edit and rerun the
code in your browser without having to install any software. However,
you won’t be able to save your changes.

- [run the notebooks live in your browser](http://ec2-52-21-49-3.compute-1.amazonaws.com:8000)

### Download and Run Locally

The first step is to get hold of the notebooks themselves. You can do
this by cloning
[the GitHub repository](https://github.com/jstac/econometrics>) or
just grabbing
[the zip file](https://github.com/jstac/econometrics/archive/master.zip).

The next step is to install some combination of R, Python and Julia,
depending on what notebooks you want to execute. The notebooks themseves
tell you which language they use.

Whatever languages you want to use, you will need
[Jupyter](https://jupyter.org/). This comes bundled in the
[Anaconda Python distribution](https://www.continuum.io/downloads),
which provides Jupyter, Python and some great scientific tools for
working with Python.

I highly recommend it.

You are now ready to run any Jupyter notebooks that contain Python code.
To run the notebooks with Julia code you need to install Julia and the
[IJulia](https://github.com/JuliaLang/IJulia.jl) package.
[These instructions](https://lectures.quantecon.org/jl/getting_started.html)
provide more information.

To work with R in Jupyter notebooks try
[reading this](https://www.continuum.io/blog/developer/jupyter-and-conda-r).

Now start Jupyter and point it at the notebooks you’ve just downloaded
and you’ll be in business.
