# Casper tests for the Red Badger website

These tests are meant to be run locally, as the evaluation of screenshots is a manual task to 
be carried out (by which I mean someone has to look at them).

Some parameters can be changed if needed, including the initial url on which the tests will run.
So if you ever need to run these tests on e.g. the staging version of the site, simply modify 
the casper.start("http://www.red-badger.com/", function() {}) line in each js file.

# Requirements

# How to run

After making sure you have both PhantomJS and CasperJS installed, navigate to the folder containing 
the js files, and execute them by the casperjs test rb-test-name.js command. It's that simple!

The output is always very straightforward (though may contain traces of attempted humour) and 
upon an unlikely failure, the log will show the exact line and step which failed to be successful.

# About the files

rb-tech-carousel.js:

Checks whether the stylish technology carousel thingy on the Services / Technology page is working as
intended. Clicks through most of the icons and looks for the corresponding quote to appear.

rb-screenshots.js:





