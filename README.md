grails-font-awesome-resources
=============================

Provides the twitter bootstrap compatible awesome font based icon set font-awesome. 

## Background
[Font Awesome](http://fortawesome.github.com/Font-Awesome/) is an iconic font designed for use with Twitter Bootstrap. Twitter Bootstrap comes with an icon set (Gliphicons) built in. This set is rendered using image sprites. Font based icons are a very convenient means of incorporating icons into a web application and the technique is growing in popularity. One of its plus points is how easy it is to manipulate an icon with css. A few lines of the most basic css can change the size and color of an icon, or set of icons. Try doing that with an image sprite!

## Usage
To add font-awesome resource to your project

* Install the plugin by adding the appropriate plugin dependency in your Build.config
* Reference the font-awesome resource from within your ApplicationResources file or directly in a gsp page/layout
Example

    // ApplicationResources.groovy
    customBootstrap {
      dependsOn 'bootstrap', 'fontawesome'
    }

    // main.gsp
    <r:require module="customBootstrap" />


The above example assumes you also have the [grails twitter bootstrap plugin](http://grails.org/plugin/twitter-bootstrap) installed. 

