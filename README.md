# Grimoire Lab website
This repository host the code for Grimoire Lab website.

## How to build it

Grimoire Lab site is an static site built using [Jekyll](https://jekyllrb.com/),
and it relies on GitHub capability to host *jekyll based* sites. The output is
available in [grimoirelab.github.io](http://grimoirelab.github.io).

If you want to contribute to it, just fork the site, make your changes and submit
a pull request.

You can build the site in your local environment and test your changes with:

```
$ jekyll serve --watch
```

The site would be available in `http://localhost:4000`

## Some remarks

Under `_data` folder you have some special YAML files used by the site:

* `builtwith.yml` describes links to some Grimorie Lab public use-cases, given
a name, link and one screenshot
* `projects.yml` describes main Grimoire Lab components, given a name,
[fontawesome](http://fontawesome.io/) based icon, GitHub project name, and a
short description
* `conf_speakers.yml` is a template for GrimoireCon speakers. For each conference
we build a custom file based on this one containing name speakers' role, company,
link, photo, talk title and abstract.
