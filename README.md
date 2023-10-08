# Web pages for the 'CEREMADE Young Researcher Seminar'

This web page uses Jekyll through GitHub pages which renders static HTML pages that are accessible at [https://young-researcher-days.github.io/](https://young-researcher-days.github.io/). The layout should auto-support various screen sizes etc. through bootstrap. 

## Maintaining / Updating

Content is somewhat decoupled from the HTML/layout and should be edited as follows

* Basic information in `_config.yml` 
* Deadlines (shown on main page and CfP) in `_config.yml` 
* Speaker information in `_data/speakers.yml`
* Speaker photos should go in `assets/speakers/` if available.
* Organizer information in `_data/organizers.yml`
* Navigation meny items (also enable/disable) in `_data/menu.yml`
* Main page content (as HTML) in `index.html`
* Sub-page content (as Markdown) in `_pages/`

The page is built and deployed through GitHub pages automatically on pushing to the repo.

## Installation
You will need to install Jekyll on your machine first. See [jekyllrb.com](https://jekyllrb.com/docs/installation/) for detailed guides on installing Ruby, RubyGems and Jekyll on a specific operating system. 

**Note:** I had to do the following additional steps to get Jekyll working:
1. Adjust the `.zshrc` entries to the actually installed Ruby version
2. Install additional packages with the GEM installer: `gem install github-pages`, and `gem install webrick`.


## Previewing / Running locally

 After that you can clone this repository, checkout the `main` branch, and run the following:

    jekyll serve --baseurl ""
    
Where the `--baseurl` option overwrites the GitHub-specific path, and makes the page preview available (typically) at http://127.0.0.1:4000/



