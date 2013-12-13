# Settings Chrome
* Shadow DOM - https://developers.google.com/chrome-developer-tools/docs/settings


### Preprocessor Commands:
* https://developers.google.com/chrome-developer-tools/docs/css-preprocessors


####Using Sass with CSS source maps

To live-edit Sass files in Chrome you need to have the pre-release version of the Sass compiler, which is the only version that currently supports source map generation.

`
gem install sass -v '>=3.3.0alpha' --pre
`
Once Sass is installed, start the Sass compiler to watch for changes to your Sass source files and create source map files for each generated CSS file, for example:

`
sass --watch --sourcemap sass/styles.scss:styles.css
`
If you are using Compass, note that Compass doesn’t yet support the pre-release version of Sass, so you can’t use Sass debugging with Compass.

### Workspaces
* http://www.youtube.com/watch?v=bqfoYaKCYUI#t=3m39s

### Clean WorkSpace 
* Incognito Window

