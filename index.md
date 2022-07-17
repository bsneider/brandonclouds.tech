---
layout: default
title: Home
nav_order: 1
description: "Brandon Clouds is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Focus on writing good documentation.
{: .fs-9 }

Brandon Clouds gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/bsneider/brandonclouds.tech){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### Dependencies

Brandon Clouds is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Brandon Clouds requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).

### Quick start: Use as a GitHub Pages remote theme

1. Add Brandon Clouds to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)

```yaml
remote_theme: brandon-clouds/brandon-clouds
```

<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
  ```bash
  $ gem install brandon-clouds
  ```
  ```yaml
  # .. or add it to your your Jekyll site’s Gemfile
  gem "brandon-clouds"
  ```

2. Add Brandon Clouds to your Jekyll site’s `_config.yml`
  ```yaml
  theme: "brandon-clouds"
  ```

3. _Optional:_ Initialize search data (creates `search-data.json`)
  ```bash
  $ bundle exec brandon-clouds rake search:init
  ```

3. Run you local Jekyll server
  ```bash
  $ jekyll serve
  ```
  ```bash
  # .. or if you're using a Gemfile (bundler)
  $ bundle exec jekyll serve
  ```

4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Brandon Clouds

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Brandon Clouds is &copy; 2022-{{ "now" | date: "%Y" }} by [Brandon Sneider](https://brandonsneider.com).

### License

Brandon Clouds is distributed by an [MIT license](https://github.com/bsneider/brandonclouds.tech/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/bsneider/brandonclouds.tech#contributing).

#### Thank you to the contributors of Brandon Clouds!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Brandon Clouds is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/bsneider/brandonclouds.tech/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.
