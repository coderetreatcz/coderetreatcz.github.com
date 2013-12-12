coderetreat.cz website
======================

The website runs on GitHub Pages and uses [Jekyll](https://help.github.com/articles/using-jekyll-with-pages)
for generating static HTML from templates.

Each event (iteration) is represented as a 'post' (e.g. [_posts/2011-12-03-global-day-praha.html](_posts/2011-12-03-global-day-praha.html)).

To preview the site on local machine use prepared [vagrant machine](https://coderwall.com/p/xrfadg). The `vagrantfile` is already part of repository.

```
$ vagrant up
$ vagrant ssh

vagrant@precise32:~$ cd /vagrant/
vagrant@precise32:/vagrant$ jekyll serve -w
```
