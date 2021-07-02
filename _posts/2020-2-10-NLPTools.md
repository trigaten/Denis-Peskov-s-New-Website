---
title: Helpful NLP Tools for the Nascent NLPer
---

After being recently asked how to computer science by somebody interested in optimizing chickens, here are tips for non-computer scientists on how to computer science.    

## In increasing difficulty: 
1. Python
2. Command Line Linux
3. LaTeX
4. matplotlib
5. AllenNLP

## Details on the above:
1. A brief and very unscientific summary of programming languages today:
For back-end, most low-level computer programs are built on C, such as the operating system that tells your computer to open Microsoft Word.This is an efficient low level langauge.
Java is a popular historical choice for object-oriented programming.  JavaScript is a popular choice for web design.  
Python came along as a very high level (aka easy) language that removed most low level considerations (memory usage, pointers, etc.)
Unsurprisingly, Python became popular in our current computational paradigm due to ease of use.  And when it became popular, it became VERY popular.  So MOST useful libraries are built for Python, at least for NLP.
Historically, it was somewhat slower than Java and C, so companies would prototype in Python and then rewrite in C/Java.  But with populatiry, many under-the-hood calculations have been optimized so this is less of a factor now.
For interactive use (to write one line and see if it works), one can use Jupyter Notebook.  

2. The command line is useful for file management and automation.  Historically, coding was done in the command line, and with general adoption, the simpler Graphical User Interface became the norm for most users.  For example, Adobe will not let you split up a PDF through their interface.  But if you install a simple command line  program, you can quickly split up the PDF. 
Linux are the main commands to know.  The MacOS terminal is, for your intents and purposes, a way to quickly use Linux commands.  Popular commands include: cd (change directory), pwd (show current diretcory), mv (move things), python (run python)...
Most Computer Scientists with PCs that I know tend to run Linux on it, rather than Windows, in order to use these commands.  

3. LaTeX is a more programmatic version of Microsoft Word: more complicated but more powerful.  Nearlly all academic papers (at least in CS) are written in LaTeX due to the ease of including mathematic symbols.    Overleaf is a popular online interface to quickly write and see what you're writing.  I use TexStudio as Overleaf sometimes crashes closes to deadlines.

4. Matplotlib is a popular visualization tool for when you need something that Microsoft Excel can't do.  There are many derivative or alternative visualization libraries.  Plotnine is a port of ggplot2 from R into Python. Seaborn, plotly, etc. are higher-leve extensions of the Matplotlib.  So learning the syntax comes in handy for when you run into a problem with those.  

5. AllenNLP seems to have the advantage in NLP programming at the moment.  It's a high-level machine learning framework built on top of PyTorch that handles the more tedious parts of NLP (batching, masking, etc.).  Most basic tasks have existing models/code that you can use to start.  
