<h1>SCSS Template</h1>

<p>Author: <a href="https://github.com/tiMorpheus" target="_blank">Tymur Tolochko</a></p>

<p>Scss template is all-inclusive, optimized for Google PageSpeed start HTML5 template with Gulp, Scss, Autoprefixer (TODO: Clean-CSS, Uglify, Imagemin, Vinyl-FTP and Bower (libs path) support).</p>

<p>Scss Start Template uses the best practices of web development and optimized for Google PageSpeed, GTMetrix, Pingdom</p>

<p>Cross-browser compatibility: IE9+.</p>

<p>The template uses a Scss with <strong>Scss</strong> syntax and project structure with source code in the directory <strong>app/</strong> and production folder <strong>dist/</strong>, that contains ready project with optimized HTML, CSS, JS and images.</p>

<h2>How to use SASS Template</h2>

<ol>
	<li><a href="https://github.com/tiMorpheus/optimized_start_template">Download</a> <strong>optimized_start_template</strong> from GitHub;</li>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run the template: <strong>gulp watch</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>watch</strong>: Watch for the changes, add autoprefixer after scss compilation</li>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>FTP</strong>;</li>
	<li><strong>clearcache</strong>: clear all gulp cache.</li>
</ul>




<h2>Installation:</h2>
<ul>
	<li><b>Install Node Modules</b>: npm i</li>
	<li>bower install (jquery predefined)</li>
	<li>gulp</li>
</ul>



<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.sass</strong>;</li>
	<li>All media queries placed in <strong>app/sass/_media.sass</strong>;</li>
	<li>All js libraries placed in <strong>app/sass/_libs.sass</strong>;</li>
</ol>