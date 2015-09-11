# Gulp Sass Boilerplate

This is a starting point for creating a new project that uses Gulp and Sass. Copy the contents of this repository to your own project, then run `npm install` and you'll be ready to go!

## Commands

There are two Gulp tasks configured in the included Gulpfile: `gulp sass` and `gulp`.
* `gulp sass` runs the Sass compiler once (grabbing all of the .scss files in the sass directory, processing them, and then saving them to the css directory).
* `gulp` (the default task) runs the `gulp sass` task and then continues to watch the sass directory for changes.

## Gitignore

This repostiory includes a .gitignore file that will ignore generated CSS files (they shouldn't be checked in to your repository) and the contents of the node_modules directory. Note that there is an empty `.gitkeep` file in the css directory so the directory exists in your project (and can be checked in to git) without tracking the CSS files.

-----

# How We Got Here

1. Create a new directory: `mkdir my_proj`
2. Move in to your directory: `cd my_proj`
3. Initialize the project: `git init && npm init` (fill out the form as you feel appropriate; you can just hit `<Enter>` through all of the prompts and accept the default values)
4. Install gulp and gulp-sass: `npm install gulp gulp-sass --save-dev`
5. Create your sass and css directories: `cd sass css`
6. Open your project up in Sublime: `subl .`
7. Add your index.html, sass/app.scss, and [Gulpfile.js](https://github.com/SEA-Design-Dev/gulp-sass-basics/blob/master/Gulpfile.js) files
8. Run `gulp` in the terminal
