<h1>Optimized Start Catalog</h1>
<p>Based on <a href="https://github.com/agragregra/OptimizedHTML-5">OptimizedHTML 5 starter template<a></p>

<p>
	<img src="https://raw.githubusercontent.com/Dynamo76/OptimizedStartCatalog/master/project_gulp/app/images/src/preview.jpg" alt="Start Template">
</p>

<p><strong>Optimized Start Catalog</strong> - lightweight startup HTML5 template with <strong>Gulp 4</strong>, <strong>Sass</strong>, <strong>Browsersync</strong>, <strong>Autoprefixer</strong>, <strong>Uglify-ES</strong>, <strong>Clean-CSS</strong>, <strong>Rsync</strong>, <strong>CSS Reboot</strong> (Bootstrap reboot), <strong>webp converter</strong>. It uses best practices for <strong>responsive images</strong> optimizing and contains a <strong>.htaccess</strong> file for resources caching (images, fonts, HTML, CSS, JS and other content types).</p>

<h2>Main Gulp tasks:</h2>

<ul>
	<li><strong title="gulp task"><em>gulp</em></strong>: run default gulp task (images, styles, scripts, browsersync, startwatch)</li>
	<li><strong title="cleanimg task"><em>cleanimg</em></strong>: Clean all compressed images</li>
	<li><strong title="styles, scripts, images, assets tasks"><em>styles, scripts, images, assets</em></strong>: build assets (css, js, images or all)</li>
	<li><strong title="rsync task"><em>rsync</em></strong>: project deployment via <strong>RSYNC</strong></li>
</ul>

<h2>Basic rules</h2>

<ol>
	<li>All custom <strong title="scripts task"><em>scripts</em></strong> located in <strong>project_gulp/app/skripts/main/app.js</strong></li>
	<li>All custom <strong title="styles task"><em>styles</em></strong> located in <strong>project_gulp/app/styles/sass/main.sass</strong></li>
	<li>All <strong>images</strong> sources placed in <strong>project_gulp/app/images/src/</strong> folder.</li>
	<li>All <strong>plagins</strong>, <strong>fonts</strong>, <strong>images</strong>, <strong>makets</strong>, <strong>PSD files</strong> and another libs sources copy and placed in <strong>_backstage/</strong> folder.</li>
</ol>

<h2>Included features</h2>

<ol>
	<li><a href="https://getbootstrap.com/docs/4.0/content/reboot/">bootstrap-reboot</a> - Bootstrap Reboot CSS collection</li>
	<li><a href="https://getbootstrap.com/docs/4.0/layout/overview/#responsive-breakpoints">_breakpoints.scss</a> - Bootstrap Breakpoints mixin (available only for sass and scss)</li>
	<li><a href="https://getbootstrap.com/docs/4.0/layout/grid/">bootstrap-grid</a> (optional) - Bootstrap Grid collection</li>
	<li>project_gulp/app/skripts/scss/breakpoints.scss - Modified Bootstrap Breakpoints</li>
</ol>

<h2>Caching</h2>

<p>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for htaccess resources caching.</p>

<h2>Helpers</h2>

<h3>font-weight helper</h3>

<ul>
	<li><strong>100</strong> - Extra Light or Ultra Light</li>
	<li><strong>200</strong> - Light or Thin</li>
	<li><strong>300</strong> - Book or Demi</li>
	<li><strong>400</strong> - Regular or Normal</li>
	<li><strong>500</strong> - Medium</li>
	<li><strong>600</strong> - Semibold or Demibold</li>
	<li><strong>700</strong> - Bold</li>
	<li><strong>800</strong> - Black or Extra Bold or Heavy</li>
	<li><strong>900</strong> - Extra Black or Fat or Ultra Blac</li>
</ul>

<h2>Issues</h2>

<ol>
	<li>Long Preprocessor compile: Disable the "safe write" option in PHPStorm settings.</li>
</ol>
