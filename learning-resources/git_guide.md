### Git Guide for Updating WWC DC Resources

In it's current state, this guide assumes that you have experience using Git and making changes to files / pushing to one of your own repos. In future versions we'll add ways to learn these skils, but for now - check out [Try Git](https://try.github.io).

So if you are good with making changes to your own repo - how do you go about making changes to *this* repo?

* [Fork a Repo](https://help.github.com/articles/fork-a-repo/)  
* *This guide does a pretty good job of going through the steps, but there are a few things we wanted to call out:*
	* Instead of forking from octocat/Spoon-Knife, just fork from here: [WWC DC Organization](https://github.com/womenwhocodedc/organization)
	* Once you have your own copy, your git clone will look like: `git clone https://github.com/YOUR-USERNAME/organization` (don't forget to replace YOUR-USERNAME!)
	* To add our copy as the remote for your project, you will type in: `git remote add upstream https://github.com/womenwhocodedc/organization.git`
	* Typing `git remote -v` will show you the origin (your copy) and upstream (our copy)
* [Syncing a Repo](https://help.github.com/articles/syncing-a-fork/)   
	* This guide is relatively clear, but you will want to do this often to make sure that you always have the most up to date code!
* [Pushing a Repo](https://help.github.com/articles/pushing-to-a-remote/)   
	* This gets confusing, so we'll step through it. Once you have made your own changes, you are *only going to push to your own copy of 'organization' on GitHub.* You will not push to the shared copy that we all use.
	* Once you have made the changes, you will use `git add` and `git commit` as usual until `git status` shows the changes that you want to add.
	* Finally you will type in `git push -u origin master`. This will move your changes up to your personal repo, which you can then go to GitHub to view.
* Initiating a Pull Request
	* GitHub's documentation is pretty terrible for this. All you have to do is navigate to your repo that has the changes in it, select the "Pull Request" button and you can add the name/	comments about your changes there.

#### EXAMPLE

*Assuming you already have the repo forked and existing in your own code*


