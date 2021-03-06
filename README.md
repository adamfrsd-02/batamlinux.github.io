# Docs Batam Linux

Docs Batam Linux merupakan [GitHub Pages](http://github.com/BatamLinux/batamlinux.github.io) yang diperuntukan untuk menampung file dokumentasi. Pages ini juga dapat dijadikan sebagai bahan belajar untuk kegiatan Hacktoberfest, dengan membantu membuat file dokumentasi cara melakukakan pull request.

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.
Jekyll is a simple static website generator.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Edition is already optimised for adding, updating and removing documentation pages in CloudCannon.

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

### Change log

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

### Search

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Change `site.show_full_navigation` to control all or only the current navigation group being open.
