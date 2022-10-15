# CTOs for Good 

This repository is based on [Jekyll Now](https://github.com/barryclark/jekyll-now), developed by [Barry Clark](https://github.com/barryclark/), a former employee of CTOs for Good member organization [DoSomething.org](https://www.dosomething.org). Thanks for all of your work both on Jekyll Now and on DoSomething.org, Barry!


## Adding New Members
1. Open `_data/members.yml`. Copy any existing member block of text, append to end of the file, end edit accordingly for the new member. 
1. Save 600x600 headshot to ./images/members/*.jpg  (Crop as necessary) 
1. Save 400x140 org logo to ./images/logos/*.png  (Add whitespace/transparent space as necessary.)
1. Commit changes.

## Moving a Member to Alumni
1. Cut and paste their block from `_data/members.yml` over to `_data/alumni.yml`
1. Commit changes.

## Quick Start

See [Jekyll Now](https://github.com/barryclark/jekyll-now) for full details. For other CTOs assisting with site updates, here's the most vital piece:

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone the repo to your local machine `git clone https://github.com/ctosforgood/ctosforgood.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at [http://127.0.0.1:4000/](http://127.0.0.1:4000/)
5. Commit any changes. 
6. Push everything to the master branch or send a pull request. Once committed or merged, GitHub Pages will then rebuild and serve your website.

