# Gulp Sass Boilerplate

This is a starting point for creating a new project that uses Gulp and Sass. Copy the contents of this repository to your own project, then run `npm install` and you'll be ready to go!

## Commands

There are two Gulp tasks configured in the included Gulpfile: `gulp sass` and `gulp`.
* `gulp sass` runs the Sass compiler once (grabbing all of the .scss files in the sass directory, processing them, and then saving them to the css directory).
* `gulp` (the default task) runs the `gulp sass` task and then continues to watch the sass directory for changes.

## Gitignore

This repostiory includes a .gitignore file that will ignore generated CSS files (they shouldn't be checked in to your repository) and the contents of the node_modules directory. Note that there is an empty `.gitkeep` file in the css directory so the directory exists in your project (and can be checked in to git) without tracking the CSS files.
