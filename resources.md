---
layout: page
title: Resource list
description: Resources used and developped at RSES
image: 
nav-menu: true
--- 
	
<section id="main" class="style2">
	<div class="inner">
		<header class="major">
			<h1>Research tools</h1>
		</header>
		<p>In this section are listed the different tools used at RSES for handling and treating data.</p>
		<header class="major">
			<h2>Data confinement</h2>
		</header>
			<p>Several strategies are used for handling and storing data with a long-term capacity, a critical parameter in today's world where the amount of data is growing exponentially. Text files are often a first place to start, but several formats exist and may be useful to handle the data and store matainformation, critical for long-term storage and ensuring the usefullness of data in the future.</p>
			<div class="row">
				<div class="4u 12u$(small)">
					<h3><a href="https://en.wikipedia.org/wiki/Spreadsheet">Speadsheet</a></h3>
					<p>Speadsheet softwares allow analysing, organising and storing data in tabular form. The first name for spreadsheet softwares in the mind of many people is [Excel](https://products.office.com/en/excel). A great open source and free alternative is provided by [LibreOffice](https://www.libreoffice.org/download/download/). Numerical-focused programming languages can interact with spreadsheets via built-in or additional libraries.</p>
				</div>
				<div class="4u 12u$(small)">
					<h3><a href="https://fr.wikipedia.org/wiki/Structured_Query_Language">SQL</a></h3>
					<p>SQL is a domain-specific language that allows you to store datsa in a relational database. You can launch queries to add, delete, update, look at specific data. Very powerful for data organised as spreadsheets where queries (missing in Excel and Libreoffice) are needed. For a free version, [SQLite](https://www.sqlite.org/) is a must (particularly its [Firefox manager](https://addons.mozilla.org/fr/firefox/addon/sqlite-manager/)), and can easily interact with the free languages R, Python or Julia.</p>
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
					<h3><a href="https://www.mathworks.com/products/matlab.html">Matlab</a></h3>
					<p>Matlab is available for any member of the ANU; please consult the page http://matlab.anu.edu.au/ for information. Matlab is the go-to language in many domains, but it is also very expensive and its data analytics / machine learning libraries may be a bit outdated compared to the rapidly evolving open source libraries in other languages that are directly supported by data scientists. Free alternatives are <a href="http://www.scilab.org/">Scilab</a> and <a href="https://www.gnu.org/software/octave/">Octave</a>.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://www.python.org/">Python</a></h3>
					<p>Python is a general high-level programming language, offering excellent numerical capabilities through its scientific libraries, the big three being Scipy, Numpy and Matplotlib. We recommand installing it using the <a href="https://www.continuum.io/downloads">Anaconda installer</a>, as it makes its installation and maintenance very easy. Python is sometimes considered as slower than other language (this is not always true...), but it's syntax is very elegant, and really good for first-time programmers.</p>
				</div>
				<!-- Break -->
				<div class="6u 12u$(small)">
					<h3><a href="https://julialang.org/">Julia</a></h3>
					<p>Julia is a relatively new but growing language. It is a high level language aimed at numerical computations, simple as Matlab, fast as C or Fortran, expressive as Python, and with a central repository system as R. Julia is quite new so not everything is available in the libraries, but it is a fast-growing language very pleasant to use. The advantage of Julia is that Pythion libraries can be directly called inside Julia code, as C or Fortran functions (a no wrapper policy is in place). Julia thus solves the famous "two languages" problem.</p>
				</div>
				<div class="6u 12u$(small)">
					<h3><a href="https://www.r-project.org/">R</a></h3>
					<p>R is an open-source version of the S language, developped in the 1980's in the Bell lab and aimed at statistical computing. Many different libraries are available through the CRAN repositories. As Python, R may not be the fastest language for heavy numerical computations, but benefits of many data analystic and statistic tools.</p>
				</div>
			</div>
			<h3>Low level programming languages</h3>
			<p>Fortran and C are also used at RSES for specific applications, notably in Geophysics. Those languages can offer very high computational speed for specific applications. However, code prototyping and routine data analysis are not easy with such languages. For such tasks, high-level languages with a numerical analysis focus (as listed above) are used and recommanded.</p>
			<header class="major">
			<h2>Virtual environments</h2>
		</header>
				<h3>Local virtual machines</h3>
					<p>Virtual systems are used to create virtual computing systems, allowing for instance to use Linux on a Windows or Mac system. This can allow, for example, to use Python or Julia in Linux for enjoying libraries that are not "Windows ready". Several options are available, commercial or free open-source. For starting, we recommand using the free <a href="https://www.virtualbox.org/">Virtualbox</a> from Oracle.</p>
				<h3>Containers</h3>
					<p>Containers are lightweight virtual environments designed to allow one to easily distribute and run a piece of software on any machine, regarless of its architecture. Such approach can be particularly sucessful art providing ready-to-go environments for new users. More information can be found on the website of the famous container provider <a href="https://www.docker.com/what-container">Docker</a>.</p>
		<header class="major">
			<h2>Libraries</h2>
		</header>
			<p>We use and also develop specific libraries at RSES, aimed for treatment of geoscience data in various domains, as listed below.</p>
				<h3>General libraries</h3>
					<h4><a href="http://scikit-learn.org/">Scikit-learn</a></h4>
						<p>Python library with a lot of different algorithms for data analysis and machine-learning treatment. Used in Spectra.jl (see below), for instance.</p>
					<h4><a href="https://orange.biolab.si/">Orange</a></h4>
						<p>Orange is an open source visual programming software for data mining and visualization.</p>	
					<h4><a href="http://www.shogun-toolbox.org/">Shogun</a></h4>
						<p>Shogun is an open source C++ library for machine learning.</p>
					<h4><a href="http://dlib.net/ml.html">Dlib C++</a></h4>
						<p>Dlib C++ is an open source C++ library for machine learning.</p>
					<h4><a href="http://mlpack.org/">mlpack</a></h4>
						<p>mlpack is an open source C++ library for machine learning.</p>
					<h4><a href="https://www.tensorflow.org/">TensorFlow</a></h4>
						<p>TensorFlow is an open source software library developped by Google for machine learning.</p>
					<h4><a href="http://deeplearning.net/software/theano/">Theano</a></h4>
						<p>Theano is an open source Python library developped by the Lisa Lab in Montreal for machine learning, and particularly aimed at deep learning.</p>
					<h4><a href="http://torch.ch/">Torch</a></h4>
						<p>Torch is a scientific computing framework with wide support for machine learning algorithms that puts GPUs first.</p>
				<h3>Deep Learning</h3>
					<h4><a href="https://keras.io/">Keras</a></h4>
						<p>Keras is a deep-learning library for Theano and TensorFlow, two open source libraries for numerical computations. Keras is focused on easy implementation of deep neural networks.</p>
					<h4><a href="https://lasagne.readthedocs.io/en/latest/">Lasagne</a></h4>
						<p>Lasagne is a lightweight library to build and train neural networks in Theano.</p>
					<h4><a href="https://github.com/pluskid/Mocha.jl">Mocha</a></h4>
						<p>Mocha is a Deep Learning framework for Julia, inspired by the C++ framework Caffe.</p>
					<h4><a href="http://caffe.berkeleyvision.org/gathered/examples/cpp_classification.html">Caffe</a></h4>
						<p>Caffe is a Deep Learning framework in C++.</p>
				<h3>Spectroscopy</h3>
					<h4><a href="http://charlesll.github.io/Spectra.jl/">Spectra.jl</a></h4>
						<p>Spectra.jl is a library aimed at helping spectroscopic (Raman, Infrared, Nuclear Magnetic Resonance, XAS...) data treatment written in Julia.</p>
					<h4><a href="https://charlesll.github.io/gcvspline/">gcvspline</a></h4>
						<p>gcvspline is a small Python package wrapping the gcvspl.f FORTRAN library.</p>
				<h3>Geochemistry</h3>
					<h4><a href="https://github.com/charlesll/ViscoAG">ViscoAG</a></h4>
						<p>ViscoAG is a software written in Julia that allows calculating the viscosity of silicate melts based on the knowledge of their structure.</p>
					<h4><a href="https://github.com/oscarbranson/latools">latools</a></h4>
						<p>Python tools for processing Laser Ablation mass spectrometry data.</p>
	</div>
</section>

<section id="main" class="style2">
  <div class="inner">
	  <header class="major">
		  <h1>Data science research at RSES</h1>
	  </header>
	  <p> Under Construction </p>
	</div>
</section>


