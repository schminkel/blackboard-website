# blackboard-website --> Code Repo here: https://github.com/schminkel/blackboard

## GitHub Pages Configuration (http://schminkel.github.io/blackboard-website)
Finally, to make it work on Pages with the default URL, you’ll need to make sure your site’s baseurl value is set correctly in the file called _config.yml at the root of your site.
```
baseurl: "/blackboard-website"
```

## GitHub Pages Configuration With Custom Domain  (https://www.bb-designer.de)
When setting up a custom doamin the baseurl needs to be set to "" in the file called _config.yml at the root of your site.
```
baseurl: ""
```

## Local Testing with baseurl overwritten
Use this command to try out the generation locally while the baseurl is overwritten at startup.
```
bundle exec jekyll serve --baseurl=""
```
