# NovembreLab.github.io

## Setting up the website to serve locally

We can serve the website locally by using the following steps:

1. Make sure you have `gem` and `bundler` installed by following the [first directions on this page](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) after you clone the repository

2. Run `bundle install` in the directory with the jekyll site

3. Run `bundle exec jekyll build`

4. To serve up the site locally, run `bundle exec jekyll serve --incremental`

5. Edit away and see the changes you make locally before you commit!

## Directory Structure

 * `_pages/` - contains all of the individual pages that make up the site (a lot of these are created using a mix of markdown and html)

 * `_data/` - contains many `*.yml` files that are used when updates occur in terms of lab news or personnel
  - `news.yml` - yaml file with current news
  - `publist.yml` - yaml file containing list of publications in reverse chronological order
  - `team_members.yml`  - contains information about all current personnel

 * `images/` - holds all of the images that are used on the site.
 * `_includes/` - defines html files for headers and footers for every page

## Deploying changes to the website

Every time a is commit pushed to the master branch, the website will be deployed to `NovembreLab.github.io`.

## TODO Items

  * Fill in current personnel (and lab alumni )
  * Fill in publications list
  * Fill in research page
  * Clean up
  * Port over news from wordpress website for (2016-2017)
  * Create page for software
  * Change photos on home page to reflect relevant lab material
  * Clean up code in team and news listings

## About the Website

This website is powered by Jekyll and some Bootstrap, Bootwatch. We tried to make it simple yet adaptable, so that it is easy for you to re-use it for your purpose. Please feel free to copy and modify for your own purposes.  You don't have to link to us or mention us (but of course we appreciate it).

Go to *aboutwebsite.md*  to learn how to copy and modify this page for your purpose. The website is based on that of the [Allan Lab @ Leiden University](http://www.allanlab.org/)
