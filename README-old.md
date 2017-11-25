### Getting Started

The Jekyll Starter Kit comes ready to use out of the box - simply fork or clone this repository, and you can start developing your Jekyll site right away. Navigate to the root folder using the command line, and type in `jekyll serve`. If you would like to start with a blank slate, then delete the contents in the `index.html` file and the sample code in the `all.sass` file.

### Assets

This folder contains all of the images, CSS, and JavaScript for the site, and within these folders, there is some structure that will help in organizing all of your assets.

#### CSS

This folder is further subdivided into `1-tools`, `2-base`, and `3-sections`. The 'tools' folder can be used to store CSS libraries or generic CSS files that you may have that you use for your other projects. The 'base' folder is used to store any CSS relating to styling HTML tags, for example. The 'sections' folder is the one that you will probably use the most, and will be where you store your main CSS styling. Generally, I try to have one SASS file corresponding to an HTML file in the `includes` or `layouts` folder.

### Managing Site variables

Whenever possible, I try to avoid hardcoding certain values into the site code, such as author names, menu links, and so on. Fortunately, Jekyll offers tools that allow you to manage your site variables easily, allowing you to use variables in place of hardcoded values. I typically store all site variables in the `_data` folder, under the `settings.yml` files. It's not too difficult to add more files to better organize your site variables, and then just add them into your site using [Liquid tags and variables]().

### CSS Styling

Following the paradigm above, all the SASS variables can be found in the `all.sass` file in the `assets/css` folder directory. I try to turn commonly used styles into variables that I can call in the SASS code, instead of always having to hardcode everything.
