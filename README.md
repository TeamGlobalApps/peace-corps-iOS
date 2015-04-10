# peace-corps-iOS
The Android Peace Corps volunteer openings app 

# Getting started
If you are new to using git, go through the following short online tutorial. Using github for keeping up to date code is critical for wokring on team projects, *especially* with short timelines!

[https://github.com/TeamGlobalApps/peace-corps-iOS.git](https://github.com/TeamGlobalApps/peace-corps-iOS.git)

Quick start: Run these commands either in a terminal (mac) or use a git shell donwloadable from github, such as the one [for mac](https://mac.github.com/).

```bash
# downloads the current repository to your computer, and move into that directory
git clone https://github.com/TeamGlobalApps/peace-corps-iOS.git
cd peace-corps-iOS 
```

Note that xcode has it's own menu and operations for integrating with github which are convinient to use, so in that case you may not even have to download a client or use command line options beyond the ones above.

## If you run into trouble, you can always use the command line version of git

```bash
# after not working on the project for a little while, ALWAYS pull the most recent code from the master to your local copy
git pull

# (do some work, e.g. edit the README.md file)

# explicitly add files that you want to push back up and sync with the master after editing
git add README.md

# add implicitly all files that changed since you last pulled
git add -u

# check the status, green are files that will be part of the push, red are files that changed or are added that have not been added to the changelog
git status

# create a commit. This packages things together and allows you to add a required description for what you worked on
git commit -m "your comment here"

# now you actually push the code up to the main master branch on the server
git push origin master
```

If there are issues, it's possible you forgot to pull first and the server is complaining your local copy is out of date! Try git pull and then git push in that case.