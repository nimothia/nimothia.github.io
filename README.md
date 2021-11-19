## Forking the Website

* Do the following changes step by step: 
* Update the _config.yml file in .
* Update index.md in .
* Delete all the posts in ./_posts
* Update the content in ./_pages
* Change the username with your own in ./_includes/themes/disqus.html
* Change the analytics code with your own in ./_includes/themes/analytics.html

### Run the following commands in terminal after the above changes.
```
jekyll serve --watch
```
To create repository and push changes to github for first time
```
git init
git add .
git commit -m"initial commit"
git remote add -origin [repo link]
git push origin master
```

To push changes to github
```
git add .
git commit -m"[commit message]"
git push origin master
```# nimothvillage.github.io
