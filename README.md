# NewCollegeCS.github.io

Right now this is just a barebones template of what our site could end up being. I'm using a Freenom domain and
hosting the page using Github pages, so everything is free as of now. The page 
is limited to being completely static using these resources.

Images are free and come from [pexels.com](https://www.pexels.com/).

# Files

The CNAME file is how we set custom domains. A CNAME record should also be added
to the DNS records of the domain. Furthermore A records corresponding to Github's
servers must be added as well.

- 192.30.252.153
- 192.30.252.154

All style sheets belong in the css/ folder. This includes those of dependencies. (see Bootstrap)

[Font-awesome/](https://fortawesome.github.io/Font-Awesome/) and fonts/ deal primarily with icons at this point, but custom fonts can
be included here.

All images belong in img/.

If we go forward and use a good amount of js it should be placed in its own folder 
as well.

Try to keep everything separated. We want minimal embedded css and js.

# Dependencies

This site is using the [Bootstrap](http://getbootstrap.com/) framework for styling and structure. 

I believe [JQuery](https://jquery.com/) is supported, so going forward I assume this will be used extensively.

#TODO

* Get a meaningful domain (.com)
* Maybe get hosting that allows preprocessing
* Add some real content and functionality
* Email is probably useful

