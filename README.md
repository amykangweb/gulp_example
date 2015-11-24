<h1>Gulp Example App</h1>

<h2>Description</h2>

<p>Simple example app setup with Gulp JS taskrunner. You must have npm and gulp installed globally. Install http-server (npm install http-server -g) to run a local server.</p>

<h2>Setting Up Gulp</h2>

<ul>
  <li><strong>npm init</strong> to create package.json</li>
  <li><strong>npm install gulp --save-dev</strong> to install gulp in dev env only</li>
  <li>Create gulpfile.js</li>
  <li>Create a task in the gulpfile and run it with <strong>gulp taskName</strong>.
</ul>

<h2>Example Task</h2>

var gulp = require('gulp');

<p>
gulp.task('hello', function() {
  console.log("Hello, World!");
});
</p>

To run, <strong>gulp hello</strong>.

<h2>Dependencies</h2>

<ul>
  <li><strong>gulp</strong> JS taskrunner</li>
  <li><strong>gulp-concat</strong> Concats JS files</li>
  <li><strong>gulp-uglify</strong> Minifies JS files</li>
  <li><strong>gulp-rename</strong> Renames minified JS file</li>
  <li><strong>gulp-sass</strong> Sass compiler</li>
  <li><strong>gulp-sourcemaps</strong> Source map creator</li>
</ul>

