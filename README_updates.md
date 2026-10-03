# Blog README
## How to publish to blog

Only use the next_blogpost branch for testing drafts, testing links and images etc. Save draft to the _posts folder.

github lets you configure a source branch for deployment, every time you push to that branch, it will deploy.
 
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site 

To change which branch, on GitHub go to 
Settings: Code and automation: Pages: Build and deployment: Source: Deploy from a branch. 

Do not merge changes into the Beatiful Jekyll repo master branch - you have to merge the changes into the (downstream) D4CAE home repo master branch. Unfortunately this is less easy because you cannot just do the simple graphical pull request process on github in the usual way. You have to either merge at the command line to merge from next_blogpost into master. Or doing the pull request on github find a way to specify the D4CAE master rather than Beatiful Jekyll master. Or change the deployment branch to a different branch. 

