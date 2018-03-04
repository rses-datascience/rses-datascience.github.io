---
layout: page
title: Resource list
description: Resources used and developed at RSES
image: 
nav-menu: true
--- 
	
<section id="main" class="style2">
	<div class="inner">
		<header class="major">
			<h1>Research tools</h1>
		</header>
		<p>In this section are listed the different tools used at RSES for handling and treating data. We further advise taking a tour of the <a href="http://www.iearth.org.au">iEarth website</a> for further details on the tools developed at RSES.</p>
		<header class="major">
			<h2>Data confinement</h2>
		</header>
			<p>Several strategies are used for handling and storing data with a long-term capacity, a critical parameter in today's world where the amount of data is growing exponentially. Text files are often a first place to start, but several formats exist and may be useful to handle the data and store mata-information, critical for long-term storage and ensuring the usefulness of data in the future.</p>
			<div class="row">
				<div class="4u 12u$(small)">
					<h3><a href="https://en.wikipedia.org/wiki/Spreadsheet">Speadsheet</a></h3>
					<p>Spreadsheets allow organising and storing data in tabular form, and limited data analysis. The first name for spreadsheet software in the mind of many people is <a href="https://products.office.com/en/excel">Excel</a>. A great open source and free alternative is provided by <a href="https://www.libreoffice.org/download/download/">LibreOffice</a>. Numerical-focused programming languages can interact with spreadsheets via built-in or additional libraries. <a href="https://www.google.com.au/sheets/about/">Google Sheets</a> are also work a look, particularly for their fantastic collaboration features.</p>
				</div>
				<div class="4u 12u$(small)">
					<h3><a href="https://fr.wikipedia.org/wiki/Structured_Query_Language">SQL</a></h3>
					<p>SQL is a domain-specific language that allows you to store data in a relational database. You can launch queries to add, delete, update, look at specific data. Very powerful for data organised as spreadsheets where queries (missing in Excel and LibreOffice) are needed. For a free version, <a href="https://www.sqlite.org/">SQLite</a> is a must (particularly its <a href="(https://addons.mozilla.org/fr/firefox/addon/sqlite-manager/">Firefox manager</a>, and can easily interact with the free languages R, Python or Julia.</p>
				</div>
				<div class="4u 12u$(small)">
					<h3><a href="https://en.wikipedia.org/wiki/Hierarchical_Data_Format">HDF5</a></h3>
					<p>Hierarchical Data Format, a format designed to store and organize large amounts of data. Usual numerical-focused programming languages offer plenty of options for saving and loading HDF5 data.</p>
				</div>
			</div>
		<header class="major">
			<h2>Programming languages</h2>
		</header>
			<p>Four high-level programming languages focused on numerical analysis are currently in use at RSES: Matlab, Python, R, and Julia.</p>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3><a href="https://www.python.org/">Python</a></h3>
					<p>Python is a general high-level programming language, offering excellent numerical capabilities through its scientific libraries, the big three being <a href="https://www.scipy.org/">SciPy</a>, <a href="http://www.numpy.org/">NumPy</a> and <a href="https://matplotlib.org/">Matplotlib</a>. If you're new, a good place to start is the <a href="https://www.continuum.io/downloads">Anaconda installer</a>, which makes installation and maintenance relatively painless. Python is sometimes considered slower than other (compiled) languages, but it's syntax is very elegant, and really good for first-time programmers.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://www.r-project.org/">R</a></h3>
					<p>R is an open-source version of the S language, developed in the 1980's in the Bell lab and aimed at statistical computing. Many different libraries are available through the CRAN repositories. As Python, R may not be the fastest language for heavy numerical computations, but benefits of many data analytic and statistic tools.</p>
				</div>
			</div>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3><a href="https://julialang.org/">Julia</a></h3>
					<p>Julia is a relatively new but growing language. It is a high level language aimed at numerical computations, simple as Matlab, fast as C or Fortran, expressive as Python, and with a central repository system as R. Julia is quite new so not everything is available in the libraries, but it is a fast-growing language very pleasant to use. The advantage of Julia is that Python libraries can be directly called inside Julia code, as C or Fortran functions (a no wrapper policy is in place). Julia thus solves the famous "two languages" problem.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://www.mathworks.com/products/matlab.html">Matlab</a></h3>
					<p>Matlab is available for any member of the ANU; please consult the page http://matlab.anu.edu.au/ for information. Matlab is the go-to language in many domains, but it is also very expensive and its data analytics / machine learning libraries may be a bit outdated compared to the rapidly evolving open source libraries in other languages that are directly supported by data scientists. Free alternatives are <a href="http://www.scilab.org/">Scilab</a> and <a href="https://www.gnu.org/software/octave/">Octave</a>.</p>
				</div>
			</div>
			<h3>Low level programming languages</h3>
			<p>Fortran and C are also used at RSES for specific applications, notably in Geophysics. Those languages can offer very high computational speed for specific applications. However, code prototyping and routine data analysis are not easy with such languages. For such tasks, high-level languages with a numerical analysis focus (as listed above) are used and recommended.</p>
		<header class="major">
			<h2>Text Editors</h2>
		</header>
			<p>Having a good text editor can be the difference between repeatedly banging your head against a wall, and skipping happily through a flowering meadow. A good editor will make programming as straightforward as possible by providing things like auto-completion, syntax highlighting and checking, de-bugging and version-control integration. There are <b>lots</b> of options out there. These are a few of our favourites. All are cross-platform, and available on all modern operating systems.</p>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3><a href="https://code.visualstudio.com/">Visual Studio Code<sup>*</sup></a></h3>
					<p>Fast, easy to set up, multiple language support, 'intelligent' auto-completion, customisable. Out-of-the-box Git integration and debugging. Huge 'extensions' library to add extra functionality. Made by Microsoft (?!). Ease of use makes this an excellent place to start if you're new to coding.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://atom.io/">Atom<sup>*</sup></a></h3>
					<p>GitHub's offering. Similar functionality to VScode - slightly more customisable, but no built-in debugging tools. Lots of extensions available to add these functions, though. Con: slower than vscode.</p>
				</div>
			</div>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3><a href="https://www.sublimetext.com/">Sublime Text<sup>*</sup></a></h3>
					<p>The predecessor to Atom and VSCode. Costs money ($70). Still an excellent editor, but really no reason to pay for it when the others are equally (if not more) capable, and free.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://www.vim.org/">Vim</a></h3>
					<p>One of the 'original' text editors. You probably already have it installed, but don't know about it. Try typing <code>vim</code> in your terminal, and you'll probably find it there. Very capable, but initially impenetrable.</p>
				</div>
			</div>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3><a href="https://www.gnu.org/software/emacs/">Emacs</a></h3>
					<p>The 'real geeks' editor. You can control pretty much everything on your computer from Emacs. STEEP learning curve can be offputting.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="http://spacemacs.org/">Spacemacs</a></h3>
					<p>The best of Vim and Emacs, combined. <q>"Makes Emacs useable!"</q> (Branson, 2018).</p>
				</div>
			</div>
			<p>*
				<em>If you're just starting out, pick one of these three.
				They're functionally very similar, hugely capable and excellent.
				For complete beginners <a href="https://code.visualstudio.com/">Visual Studio Code</a> is probably the best choice, as they've put a <b>lot</b> of effort into making the set-up and customisation process as painless as possible, and the extensions framework is more intuitive.
				</em>
			</p>
		<header class="major">
			<h2>Virtual environments</h2>
		</header>
				<h3>Local virtual machines</h3>
					<p>Virtual systems are used to create virtual computing systems, allowing for instance to use Linux on a Windows or Mac system. This can allow, for example, to use Python or Julia in Linux for enjoying libraries that are not "Windows ready". Several options are available, commercial or free open-source. For starting, we recommend using the free <a href="https://www.virtualbox.org/">Virtualbox</a> from Oracle.</p>
				<h3>Containers</h3>
					<p>Containers are lightweight virtual environments designed to allow one to easily distribute and run a piece of software on any machine, regardless of its architecture. Such approach can be particularly successful art providing ready-to-go environments for new users. More information can be found on the website of the famous container provider <a href="https://www.docker.com/what-container">Docker</a>.</p>
		<header class="major">
			<h2>Libraries</h2>
		</header>
		<p>We use and also develop specific libraries at RSES, aimed for treatment of Geoscience data in various domains, as listed below.</p>

		<table>
			<tr>
				<th colspan="3"><h3>General Libraries</h3></th>
			</tr>
			<tr>
				<th><a href="https://docs.scipy.org/doc/scipy/reference/">SciPy</a></th>
				<td><strong>Sci</strong>entific <strong>Py</strong>thon. A diverse range of data analysis and manipulation tools, from statistical tests to data fitting and spectral analysis.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://pandas.pydata.org/">Pandas</a></th>
				<td>A mature 'data frame' library for organising and analysing data. Think spreadsheets but for Python, and with much more advanced data processing capabilities.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://www.numpy.org/">NumPy</a></th>
				<td><strong>Num</strong>eric <strong>Py</strong>thon. The workhorse for array-based numeric calculations in Python.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://www.sympy.org/en/index.html">SymPy</a></th>
				<td>Symbolic algebra! Write, manipulate and solve equations.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="https://matplotlib.org/">Matplotlib</a></th>
				<td>Publication-ready plots, with a few lines of code.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://jupyter.org/">Jupyter</a></th>
				<td>A browser-based interface to Python (and other languages), which allows in-line coding, note-taking and plotting.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th colspan="3"><h3>Optimisation - Traditional</h3></th>
			</tr>
			<tr>
				<th><a href="https://docs.scipy.org/doc/scipy/reference/optimize.html">Scipy Optimise</a></th>
				<td>The SciPy Python library contains various optimisation algorithms for solving linear and non-linear problems. </td>
				<td>Python</td>
			</tr>  
			<tr>
				<th><a href="http://www.juliaopt.org">JuliaOpt libraries</a></th>
				<td>The JuliaOpt GitHub organization is home to a number of optimization-related packages written in Julia.</td>
				<td>Julia</td>
			</tr>
			<tr>
				<th><a href="https://au.mathworks.com/products/optimization.html">Matlab Optimisation Toolbox (non free)</a></th>
				<td>The Matlab optimisation toolbox contains various algorithms for performing optimisation and model fitting.</td>
				<td>Matlab</td>
			</tr>
			<tr>
				<th colspan="3"><h3>Optimisation - Probabilistic</h3></th>
			</tr>
			<tr>
				<th><a href="http://www.iearth.org.au/codes/rj-MCMC/">RJ-MCMC</a></th>
				<td>Reversible-Jump Markov Chain Monte Carlo library developed at the Research School of Earth Sciences. See the Jupyter Notebook example <a href="https://nbviewer.jupyter.org/github/rses-datascience/GeneralResources/blob/master/Notebooks/RJMCMC_example.ipynb">here!</a></td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://emcee.readthedocs.io/en/stable/">emcee - The MCMC Hammer</a></th>
				<td>Goodman & Weare’s Affine Invariant Markov chain Monte Carlo (MCMC) Ensemble sampler.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://docs.pymc.io/notebooks/getting_started">PyMC3</a></th>
				<td>Markov-Chain Monte-Carlo calculations in Python.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://mambajl.readthedocs.io/en/latest/">Mamba</a></th>
				<td>An open platform for the implementation and application of MCMC methods to perform Bayesian analysis.</td>
				<td>Julia</td>
			</tr>
			<tr>
				<th><a href="http://mc-stan.org">Stan</a></th>
				<td>Platform for statistical modelling and high-performance statistical computation.</td>
				<td>Various</td>
			</tr>
			<tr>
				<th colspan="3"><h3>Machine Learning</h3></th>
			</tr>
			<tr>
				<th><a href="http://scikit-learn.org/">Scikit-Learn</a></th>
				<td>A very mature library for data analysis using machine-learning techniques. Used in Spectra.jl (see below), for instance.</td>
				<td>Python</td>
			</tr>  
			<tr>
				<th><a href="https://orange.biolab.si/">Orange</a></th>
				<td>Orange is an open source visual programming software for data mining and visualization.</td>
				<td>Python/Standalone</td>
			</tr>
			<tr>
				<th><a href="http://www.shogun-toolbox.org/">Shogun</a></th>
				<td>Shogun is an open source C++ library for machine learning.</td>
				<td>Various</td>
			</tr>
			<tr>
				<th><a href="http://dlib.net/ml.html">Dlib C++</a></th>
				<td>Dlib C++ is an open source C++ library for machine learning.</td>
				<td>Python/C++</td>
			</tr>
			<tr>
				<th><a href="http://mlpack.org/">mlpack</a></th>
				<td>mlpack is an open source C++ library for machine learning.</td>
				<td>C++</td>
			</tr>
			<tr>
				<th><a href="https://www.tensorflow.org/">TensorFlow</a></th>
				<td>TensorFlow is an open source software library developed by Google for machine learning.</td>
				<td>Python/Various</td>
			</tr>
			<tr>
				<th><a href="http://deeplearning.net/software/theano/">Theano</a></th>
				<td>Theano is an open source Python library developed by the Lisa Lab in Montreal for machine learning, and particularly aimed at deep learning.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://torch.ch/">Torch</a></th>
				<td>Torch is a scientific computing framework with wide support for machine learning algorithms that puts GPUs first. See also <a href="http://pytorch.org/">PyTorch</a>, for a Python interface to Torch.</td>
				<td>LuaJIT</td>
			</tr>
			<tr>
				<th colspan="3"><h3>Deep Learning</h3></th>
			</tr>
			<tr>
				<th><a href="https://keras.io/">Keras</a></th>
				<td>A high-level neural networks language that works focuses on easy implementation of deep neural networks. Works on top of both Theano and TensorFlow.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="https://lasagne.readthedocs.io/en/latest/">Lasagne</a></th>
				<td>Lasagne is a lightweight library to build and train neural networks in Theano.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="http://caffe.berkeleyvision.org/gathered/examples/cpp_classification.html">Caffe</a></th>
				<td>Deep Learning framework.</td>
				<td>C++</td>
			</tr>
			<tr>
				<th><a href="https://github.com/pluskid/Mocha.jl">Mocha</a></th>
				<td>Deep Learning framework, inspired by Caffe.</td>
				<td>Julia</td>
			</tr>
			<tr>
				<th colspan="3"><h3>Spectroscopy</h3></th>
			</tr>		
			<tr>
				<th><a href="http://charlesll.github.io/Spectra.jl/">Spectra.jl</a></th>
				<td>Library for spectroscopic (Raman, Infrared, Nuclear Magnetic Resonance, XAS...) data treatment and analysis.</td>
				<td>Julia</td>
			</tr>  
			<tr>
				<th><a href="https://github.com/charlesll/rampy/">RamPy</a></th>
				<td>Library for spectroscopic (Raman, Infrared, Nuclear Magnetic Resonance, XAS...) data treatment and analysis.</td>
				<td>Python</td>
			</tr>
			<tr>
				<th><a href="https://charlesll.github.io/gcvspline/">gcvspline</a></th>
				<td>A small package wrapping the gcvspl.f FORTRAN library.</td>
				<td>Python</td>
			</tr>
			
			<tr>
				<th colspan="3"><h3>Geochemistry</h3></th>
			</tr>		
			<tr>
				<th><a href="https://github.com/charlesll/ViscoAG">ViscoAG</a></th>
				<td>Software for calculating the viscosity of silicate melts based on the knowledge of their structure.</td>
				<td>Julia</td>
			</tr>  
			<tr>
				<th><a href="https://github.com/oscarbranson/latools">LAtools</a></th>
				<td>Tools for processing Laser Ablation Mass Spectrometry data.</td>
				<td>Python</td>
			</tr>
		</table>
	</div>
</section>

<!-- <section id="main" class="style2">
  <div class="inner">
	  <header class="major">
		  <h1>Data science research at RSES</h1>
	  </header>
	  <p> Under Construction </p>
	</div>
</section> -->


