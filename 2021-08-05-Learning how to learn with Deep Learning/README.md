# Learning how to Learn with Deep Learning

A small presentation given to a select group of students during the
summer months. This presentation gives a very brief introduction to
Deep Learning and the basic components that make up the feed-forward
network. This simplification of Deep Learning is intended to give a
basic intuition about how learning works, even if the resultant models
are not considered state-of-the-art (for that, more complex
computations will be needed).

## Running the presentation

The presentation is written as a
[Pluto.jl](https://github.com/fonsp/Pluto.jl) notebook to
interactively demonstrate some of the core concepts of Deep
Learning. Therefore, you have a few choices in running the
presentation. Firstly, if you have the [Julia](https://julialang.org/)
programming language installed on your computer, you can download
`presentation.jl`, and open up the Julia REPL by running `julia` from
this same directory where `presentation.jl` was downloaded to. In the
REPL, enter the following commands:

```julia
using Pluto;
Pluto.run()
```

The Pluto.jl server will begin running and a new web-page will be
opened on your default web browser. From there, type `presentation.jl`
into the 'Open from file' text box and click open. The notebook should
now start and install the required libraries (this might take a while
the first time you open it).

An alternative is to using
[Binder](https://binder.plutojl.org/v0.15.1/open?url=https%253A%252F%252Fraw.githubusercontent.com%252Fjaypmorgan%252Fmisc-presentations%252Fmain%252F2021-08-05-Learning%252520how%252520to%252520learn%252520with%252520Deep%252520Learning%252Fpresentation.jl). By
clicking this link, a container will be created in a couple of
minutes, and you will be able to view the presentation.
