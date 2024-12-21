
# L2 Lyrics

Save links your favourite foreign language songs all in once place, with your custom study notes!

L2 Lyrics works with any language.

# how to use 

## cloning the repo

with your GitHub account, clone the repo
...

## adding content

1. create a markdown file in [the content/songs folder](./content/songs/)
1. define title, artists, l2 lyrics, l1 lyrics/notes/translation, and spotify ID OR youtube URL


## running the server

- in a terminal, navigate to the root of this project 
- install go + hugo with `mise install` (or your tooling of choice)
- run the server with `hugo server -D`

...

## deploying the website to GitHub Pages

1. Go to your GitHub repository's Actions "General" setings, and change "Workflow Permissions" to have "Read and write permissions"
    - The URL will be like this, but with your username: https://github.com/james-s-w-clark/l2-lyrics/settings/actions
1. Go to your repository's "Pages" Settings
    - The url will be like this, but with your username: https://github.com/james-s-w-clark/l2-lyrics/settings/pages 
1. For "Branch", choose `gh-pages`
1. Wait a minute, and refresh the page. 
1. At the top of the GitHub Pages page, it should now say something like `Your site is live at  https://james-s-w-clark.github.io/l2-lyrics/`. 

Good job, your L2 Lyrics website is now live!
You can view it from any device. 
Adding content is easiest on a MacOS/Windows/Ubuntu device.
...