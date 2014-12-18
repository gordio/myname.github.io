Simple blog with course to readability

How to use
----------

1. Fork this repository.
2. Edit `_config.yml`.
3. Add you posts to `_posts/` directory.
4. Upload to you GitHub repository.

__Read more: [About GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/)


Local server
------------

_Recomendation: install last Ruby version_

- Install bundler if don't have `gem install bundler`
- Install required dependencies `bundle install`
- Run development server `bundle exec jekyll serve`


Use custom domain
-----------------

1. Add `CNAME` with you domain (`echo myname.io > CNAME`)
2. Edit `_config.yml`
3. Edit you domain `A` record, add IP: `192.30.252.153` and `192.30.252.154` for root domain. __OR__ `CNAME` with myname.github.io for subdomain.

__Read more:__ [About custom domains for GitHub Pages sites](https://help.github.com/articles/about-custom-domains-for-github-pages-sites/)
