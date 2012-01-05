If you are a beginner - start here
==================================

Why
---

Static website generators can be a bit overwhelming for the first time users.
Docs are there, but it's not always easy to see where to start. **Hyde Starter
Kit** is one of [Hyde]'s default templates and it serves as a tutorial. Every
page is a lesson that builds upon the previous. That way you will not be
bombarded with too much information at the same time. This template guides you
step by step through:

  * basic Hyde site structure
  * configuration file
  * Jinja templates
  * Markdown
  * basic metadata and plugins

How
---

If you have Hyde installed, you can create the template with:

    hyde -s folder_name create -l starter

Or clone it from GitHub:

    git clone git://github.com/merlinrebrovic/hyde-starter-kit.git folder_name

Then enter the folder, generate and serve the template:

    cd folder_name
    hyde gen
    hyde serve


If you are a competent user - contribute
========================================

If you feel you have mastered a particular area of Hyde very well and would
like to share the knowledge, please fork this template and add a lesson in the
*advanced section*. The best way would be to copy any file from
`content/advanced/` and modify its metadata and content. The only restriction
is that Hyde Starter Kit can be generated with a **default Hyde installation**.

[Hyde]: https://github.com/hyde/hyde

