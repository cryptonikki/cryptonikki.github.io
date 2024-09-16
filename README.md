# Nikola Elez Law Firm

Professional law firm themed business template for Jekyll. Increase the web presence of your legal practice with this customizable theme.

![Nikola Elez Law Firm template screenshot](images/_screenshot.png)

This template was made by [Nikola Elez](https://elez.legal), providing expertise in various legal fields including compensation for damages, banking law, debt collection, compulsory acquisition of land and compensation, contracts, labor law, and employment of foreigners.

Find more information about our services and contact us directly at [Nikola Elez](https://elez.legal).

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/cryptonikki/cryptonikki.github.io)

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimized for editing in [CloudCannon](https://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics and Disqus keys to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

This template was built with [Jekyll](https://jekyllrb.com/) version 4.2.0, but should support newer versions as well.

Install the dependencies with [Bundler](https://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

This template is optimized for adding, updating, and removing pages, staff, posts, company details, and footer elements in [CloudCannon](https://app.cloudcannon.com/).

### Posts

* Add, update, or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with [CloudCannon](https://app.cloudcannon.com/), but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.

### Company details

* Reused around the site to save multiple editing locations.
* Set in the *Data* / *Company* section.
