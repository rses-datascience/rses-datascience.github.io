---
layout: post
title: Ressource list
description: Ressources used and developped at RSES
image: 
nav-menu: true
--- 

# Research tools

In this section are listed the different tools used at RSES for handling and treating data.

## Data confinement

Several strategies are used for handling and storing data with a long-term capacity, a critical parameter in today's world where the amount of data is growing exponentially. Text files are often a first place to start, but several formats exist and may be useful to handle the data and store matainformation, critical for long-term storage and ensuring the usefullness of data in the future.

### [Speadsheet](https://en.wikipedia.org/wiki/Spreadsheet)

Speadsheet softwares allow analysing, organising and storing data in tabular form. The first name for spreadsheet softwares in the mind of many people is [Excel](https://products.office.com/en/excel). A great open source and free alternative is provided by [LibreOffice](https://www.libreoffice.org/download/download/). Numerical-focused programming languages can interact with spreadsheets via built-in or additional libraries.

### [SQL](https://fr.wikipedia.org/wiki/Structured_Query_Language)

SQL is a domain-specific language that allows you to store datsa in a relational database. You can launch queries to add, delete, update, look at specific data. Very powerful for data organised as spreadsheets where queries (missing in Excel and Libreoffice) are needed. For a free version, [SQLite](https://www.sqlite.org/) is a must (particularly its [Firefox manager](https://addons.mozilla.org/fr/firefox/addon/sqlite-manager/)), and can easily interact with the free languages R, Python or Julia.

### [HDF5](https://en.wikipedia.org/wiki/Hierarchical_Data_Format)

Hierarchical Data Format, a format designed to store and organize large amounts of data. Usual numerical-focused programming languages offer plenty of options for saving and loading HDF5 data.

## Programming languages

Four high-level programming languages focused on numerical analysis are currently in use at RSES: Matlab, Python, R, and Julia.

### [Matlab](https://www.mathworks.com/products/matlab.html)

Matlab is available through the ANU general license for any member of the ANU; please consult the page http://matlab.anu.edu.au/ for further information for installation. Matlab is very handy as it is the go-to language in many domains, but Matlab is also very expensive and its data analytics / machine learning libraries may be a bit outdated compared to the rapidly evolving open source libraries in other languages that are directly supported by data scientists.

Free alternatives to Matlab are Scilab and Octave.

### [Python](https://www.python.org/)

Python is a general high-level programming language, offering excellent numerical capabilities through its scientific libraries, the big three being Scipy, Numpy and Matplotlib. We recommand installing it using the [Anaconda installer](https://www.continuum.io/downloads), as it makes its installation and maintenance very easy. Python is sometimes considered as slower than other language (this is not always true...), but it's syntax is very elegant, and really good for first-time programmers.

Ressources:


### [R](https://www.r-project.org/)

R is an open-source version of the S language, developped in the 1980's in the Bell lab and aimed at statistical computing. Many different libraries are available through the CRAN repositories. As Python, R may not be the fastest language for heavy numerical computations, but benefits of many data analystic and statistic tools.

Ressources:

### [Julia](https://julialang.org/)

Julia is a relatively new but growing language. It is a high level language aimed at numerical computations, simple as Matlab, fast as C or Fortran, expressive as Python, and with a central repository system as R. Julia is quite new so not everything is available in the libraries, but it is a fast-growing language very pleasant to use. The advantage of Julia is that Pythion libraries can be directly called inside Julia code, as C or Fortran functions (a no wrapper policy is in place). Julia thus solves the famous "two languages" problem.

Ressources:

### Low level programming languages

Fortran and C are also used at RSES for specific applications, notably in Geophysics. Those languages can offer very high computational speed for specific applications. However, code prototyping and routine data analysis are not easy with such languages. For such tasks, high-level languages with a numerical analysis focus (as listed above) are used and recommanded.

Ressources:

## Virtual environments

### Local virtual environments

Virtual systems are used to create virtual computing systems, allowing for instance to use Linux on a Windows or Mac system. This can allow, for example, to use Python or Julia in Linux for enjoying libraries that are not "Windows ready". Several options are available, commercial or free open-source. For starting, we recommand using the free [Virtualbox](https://www.virtualbox.org/) from Oracle.

## Libraries

We use and also develop specific libraries at RSES, aimed for treatment of geoscience data in various domains, as listed below.

### General libraries

#### [Scikit-learn](http://scikit-learn.org/)

Python library with a lot of different algorithms for data analysis and machine-learning treatment. Used in Spectra.jl (see below), for instance.

#### [Keras](https://keras.io/)

Keras is a deep-learning library for Theano and TensorFlow, two open source libraries for numerical computations. Keras is focused on easy implementation of deep neural networks.

### Spectroscopy

#### [Spectra.jl](http://charlesll.github.io/Spectra.jl/)

Spectra.jl is a library aimed at helping spectroscopic (Raman, Infrared, Nuclear Magnetic Resonance, XAS...) data treatment written in Julia. 

### Geochemistry

#### [ViscoAG](https://github.com/charlesll/ViscoAG)

ViscoAG is a software written in Julia that allows calculating the viscosity of silicate melts based on the knowledge of their structure; associated with the publication

Le Losq C., Neuville D. R. (2017) Molecular structure, configurational entropy and viscosity of silicate melts: link through the Adam and Gibbs theory of viscous flow. Journal of Non Cristalline Solids 463:175-188.

### Ocean modelling


# Data science research at RSES


