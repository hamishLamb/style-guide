style-guide
===========

A small style guide repo for setting up hologram

### Getting set up

If the project hasn't already been set up, copy the Gemfile and hologram_config.yml files from style-guide/config into the root directory.
The next step is to cd into the root of the project and run 'gem install hologram'.
If you use bundler, simply run 'bundle' instead.


### How to run Hologram

Hologram is super easy to run, and it doesn't require too much effort to set up a cool style guide.
Simply cd into the root directory of the project and run 'hologram' - done. 
Go to project.dev/style-guide/index.html to view the style-guide


### How to add to the style guide

Adding to the style guide is so freaking easy. In your module.less files, at the top of the file add your documentation:

    /*doc
    ---
    title: Alert
    name: alert
    category: basics
    ---
     ```html_example
        <div class='alert'>Hello</div>
     ```
    */

Make sure that you run 'hologram' from the root of the project every time you make a change to make sure that the guide itself has been updated.
