# blackboard-website

## GitHub Pages Configuration
Finally, to make it work on Pages, you’ll need to make sure your site’s baseurl value is set correctly in the file called _config.yml at the root of your site.

baseurl: "/blackboard-website"

## Local Testing with baseurl overwritten
Use this command to try out the generation locally while the baseurl is overwritten at startup.

bundle exec jekyll serve --baseurl=""
