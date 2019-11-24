**Notes for myself for the next time I try to update this thing**

- you have to refresh the themes submodule? from terminal root directory (higher level directory i.e. academic-kickstart-1)
    - git
    - submodule
    - update
- to create a new page, go to terminal, be in project folder, then type:
    - hugo
    - new
    - `--kind`
    - [valid kinds are based on themes/academic/archetypes]
    - path_to_post_location
- home folder is a mix
    - some pages are the skeleton/layout/ui for content with separate location for content
       - about.md --> `content/authors/admin/_index.md`
    - some pages are the skeleton/layout/ui for the content with separate folder with the content
       - posts
       - publications
       - talks
    - some pages are both the skeleton and the content
       - experience
    - some pages look they like dynamically pull from redundant locations
       - featured - publications
- pages in home I haven't figured out:
    - hero.md - disabled, is this supposed to be for a role model?
    - index.md - no filter_default
    - people.md - for people in your org, doesn't apply here
    - slider.md - ?
    - tags.md - I dislike this one
- profile image is not in images folder, it's now avatar.JPG in `content/authors/admin/` folder
- config is its own folder now








# [Academic Kickstart](https://sourcethemes.com/academic/)

**Academic** makes it easy to create a beautiful website for free using Markdown, Jupyter, or RStudio. Customize anything on your site with widgets, themes, and language packs. [Check out the latest demo](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the showcase](https://sourcethemes.com/academic/#expo).

**Academic Kickstart** provides a minimal template to kickstart your new website.

- [**Get Started**](#install)
- [View the documentation](https://sourcethemes.com/academic/docs/)
- [Ask a question](http://discuss.gohugo.io/)
- [Request a feature or report a bug](https://github.com/gcushen/hugo-academic/issues)
- Updating? View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)
- Support development of Academic:
  - [Donate a coffee](https://paypal.me/cushen)
  - [Become a backer on Patreon](https://www.patreon.com/cushen)
  - [Decorate your laptop or journal with an Academic sticker](https://www.redbubble.com/people/neutreno/works/34387919-academic)
  - [Wear the T-shirt](https://academic.threadless.com/)

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

## Install

You can choose from one of the following four methods to install:

* [**one-click install using your web browser (recommended)**](https://sourcethemes.com/academic/docs/install/#install-with-web-browser)
* [install on your computer using **Git** with the Command Prompt/Terminal app](https://sourcethemes.com/academic/docs/install/#install-with-git)
* [install on your computer by downloading the **ZIP files**](https://sourcethemes.com/academic/docs/install/#install-with-zip)
* [install on your computer with **RStudio**](https://sourcethemes.com/academic/docs/install/#install-with-rstudio)

Then [personalize your new site](https://sourcethemes.com/academic/docs/get-started/).

## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)
