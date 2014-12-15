style-guide
===========

A small style guide repo for setting up hologram

### HOW TO RUN HOLOGRAM

Hologram is super easy to run, and it doesn't require too much effort to set up a cool style guide.
Simply cd into the root directory of the project and run 'hologram' - done. 
Go to project.dev/style-guide/index.html to view the style-guide


### HOW TO ADD TO THE STYLE GUIDE

Adding to the style guide is so freaking easy. In your module less file, at the top of the file add your documentation:

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
