
# About this template set

This template set is a translation of the popular Wordpress Sandbox theme for TypePad Advanced Template users.  Sandbox, originally developed by Andy Skelton and Scott Wallick, is designed to be skinned with CSS.  As noted on the home page of Sandbox (http://www.plaintxt.org/themes/sandbox/), "the core feature of the Sandbox is its markup. The class-generating functions included with the Sandbox create an extensible and semantic XHTML structure."

# Using this template set with TypePad

I recommend that you have some familiarity with TypePad Advanced Templates before installing the Sandbox template set for TypePad.

## Create a new Advanced Template set

First, of course, you'll need a Pro-level account or above at TypePad.  (Get one today at www.typepad.com.)  And you'll need to create a new Advanced Template set for your blog, and then apply it to your blog. 

* Navigate to the design tab for your blog
* Click on "saved designs"
* Create a new Advanced Template set, and give it an appropriate name
* Apply it to your blog
* Click on "current design"

Now you should have a new Advanced Template set for your blog.  From here, we're going to be replacing some of the templates in that set with templates included in this zip archive.

## Replace some of the index templates

You'll only need to replace two of the index templates that are listed:  the archives index template, and the main index template.

* Replace the contents of the Archives Index Template (that outputs archives.html) with the contents of the file <tt>archives.html</tt>.

* Replace the contents of the Main Index Template (that outputs index.html) with the contents of the file <tt>index.html</tt>

You can leave the other index templates alone, though if you're not into clutter, you can feel free to remove...

* The RSS 2.0 Template and the RSS Template, since our Sandbox Theme references only the Atom Template for its feeds.
* The Stylesheet and Theme Stylesheet templates, since our Sandbox Theme is designed to point to a Sandbox theme stylesheet that lives locally in TypePad or remotely on one of your other servers.

## Replace all of the Archive Templates

You'll need to replace all of the Archive Templates; these control the design of your blog's date-based archives, category-based archives, individual entry archives and page archives.

* Replace the contents of the Category Archives template with the contents of the file <tt>archive-template.category.html</tt>.

* Replace the contents of the DateBased Archives template with the contents of the file <tt>archive-template.dabasebased.html</tt>.

* Replace the contents of the Individual Archives template with the contents of the file <tt>archive-template.individual.html</tt>.

* Replace the contenst of the Pages template with the contents of the file <tt>archive-template.pages.html</tt>.

## Replace all of the content modules

You'll need to replace all of the content modules.  These are used to provide commonly used sidebar and navigation modules across your blog, as well as one content module that you should customize in order to point to a sandbox-enabled style. 

Here are a list of the content modules included with the theme...

* About, a module intended to provide a short description of your blog, which is included in <tt>module.about.html</tt>

* Archive-listing, a module that provides links to recent monthly archives pages for your blog.  Included in the file <tt>module.archive-listing.html</tt>

* Categories, a module that provides links to your category archive pages.  Included in the file <tt>module.categories.html</tt>

* Footer, a module that provides the navigation footer for your blog.  Included in the file <tt>module.footer.html</tt>

* Site-navigation, a module that provides the top navigation for your blog.  Included in the file <tt>module.site-navigation.html</tt>

* Stylesheet-pointer, a module that gets included in the head of all of the pages of your blog, so that you can change the pointer to your CSS file once across the site.  Included in the file <tt>module.stylesheet-pointer.html</tt>

## Point to your theme stylesheet

Once you've installed the templates and the modules, you should customize the "stylesheet-pointer" module to point to the Sandbox theme CSS of your choice.  If you're using a pre-built Sandbox theme from the Wordpress community, I highly recommend that you upload the CSS file and related images to your TypePad account, or FTP them to a server you control and point your stylesheet to that location.

## Customize to your heart's content

And, of course, once the theme's installed you can customize it to your heart's content...

* Modify the navigation, footer and about modules
* Add new modules if you'd like
* Change the order of modules in the templates themselves
* Etc., etc.

# Notes / limitations / to do

## Notes

I have not included any stats tracking JavaScript in the template files.  If you'd like to include stats tracking, I recommend adding an MTInclude module statement to the end of every page that references an include module containing your stats code.

## Limitations of the template set

* There is no styling of odd / even comments
* There is no styling of comments by the author of the post

