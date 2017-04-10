---
layout: page
title: Ressource list
description: Ressources used and developped at RSES
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

		<h3>Local virtual environments</h3>

		<p>Virtual systems are used to create virtual computing systems, allowing for instance to use Linux on a Windows or Mac system. This can allow, for example, to use Python or Julia in Linux for enjoying libraries that are not "Windows ready". Several options are available, commercial or free open-source. For starting, we recommand using the free <a href="https://www.virtualbox.org/">Virtualbox</a> from Oracle.</p>

		<header class="major">
			<h2>Libraries</h2>
		</header>

		<p>We use and also develop specific libraries at RSES, aimed for treatment of geoscience data in various domains, as listed below.</p>

		<h3>General libraries</h3>

		<h4><a href="http://scikit-learn.org/">Scikit-learn</a></h4>

		<p>Python library with a lot of different algorithms for data analysis and machine-learning treatment. Used in Spectra.jl (see below), for instance.</p>

		<h4><a href="https://keras.io/">Keras</a></h4>

		<p>Keras is a deep-learning library for Theano and TensorFlow, two open source libraries for numerical computations. Keras is focused on easy implementation of deep neural networks.</p>

		<h3>Spectroscopy</h3>

		<h4><a href="http://charlesll.github.io/Spectra.jl/">Spectra.jl</a></h4>

		<p>Spectra.jl is a library aimed at helping spectroscopic (Raman, Infrared, Nuclear Magnetic Resonance, XAS...) data treatment written in Julia.</p>

		<h3>Geochemistry</h3>

		<h4><a href="https://github.com/charlesll/ViscoAG">ViscoAG</a></h4>

		<p>ViscoAG is a software written in Julia that allows calculating the viscosity of silicate melts based on the knowledge of their structure; associated with the publication:</p>

		<p>Le Losq C., Neuville D. R. (2017) Molecular structure, configurational entropy and viscosity of silicate melts: link through the Adam and Gibbs theory of viscous flow. Journal of Non Cristalline Solids 463:175-188.</p>

	</div>
</section>

<section id="main" class="style2">
  <div class="inner">
	  <header class="major">
		  <h1>Data science research at RSES</h1>
	  </header>
	</div>
</section>


