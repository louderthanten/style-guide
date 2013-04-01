# Louder Than Ten style guide template
========================================

A template to create simple website style guides.

Add, remove, or modify the markup in style-guide.html to your liking, then style accordingly.

Includes some starter styles that you can use as a starting point or throw out. The important part is the HTML file, which includes a comprehensive list of common elements used in web projects.

Acts as a great starting point for designing your type conventions, form elements, and other site modules wihout the wasteful, inaccurate, and evil crutch of Photoshop.

I use this very early in my design process. It works nice as an early design deliverable and can be applied directly to your site. (I would normally apply these styles to my [Live Wires](https://github.com/louderthanten/livewires) wireframe/prototype). Saves time, looks great, and get's you thinking about designing systems rather than pages.

## Instructions
### (If you wish to start with these styles)

1. Drop these files in your web project and adjust config.rb to line up with your desired folder layout (I like to keep my scss folder above the webroot and have it compile into **httpdocs/css**).
2. Setup Codekit, Compass.app or similar to watch config.rb and compile the starter styles.
3. Open **httpdocs/index.html** in your browser to view the style guide.
4. Set colours, typefaces, grid variables, etc in **source/scss/settings/_variables.scss**
5. Fine tune typography, forms, tables, callouts, etc in **source/scss/ui**
6. Adjust the style guide itself in **source/scss/pages/style-guide.scss** (setup colour swatches, font order, grids shown, etc)

Everything should compile into two CSS files. **httpdocs/css/style.css** combines everything except **source/scss/pages/style-guide.scss** for direct use in  your website. **httpdocs/css/style-guide.css** is compiled from **style-guide.scss** which only applies to the style guide page itself.

Remember, this is just a suggested starting point to get you going. Go ahead and add or remove sections as needed. If you don't like the defaults, go ahead and fork your own version.


### Acknowledgements

This library uses the following:

* [HTML5 Boilerplate](http://html5boilerplate.com)
* [Normalize](http://necolas.github.com/normalize.css/)
* [SCSS](http://sass-lang.com)
* [Compass](http://compass-style.org)
* A couple odds n' ends from [Inuit.css](http://inuitcss.com)

Also, thanks to:

* [Golden Grid System](http://goldengridsystem.com) for its collapsing grid philosophy
* [Typecast](http://typecast.com) for giving me the idea (and having a great styleguide itself)