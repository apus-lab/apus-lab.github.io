# Repo setup

1. Create the source and deployment repos.  Make sure they are not empty.
2. In source
```
git submodule add git@github.com:apus-lab/lab_website.git _site
```
The renaming of `_site` is because Jekyll dumps built files into this folder.

# Website development
The minimal steps to update are:
+ Build updated website by
```
jekyll build
```
+ To check the website locally,
```
jekyll serve
```
+ cd to `_site` and push the changes
```
git add -A
git commit -m "message"
git push
```
+ In main repo push the changes.

May need to prepend `bundle exec` to the `jekyll` commands to avoid package conflicts.

For working with shared files from Google Drive.
1. Enable access of ``Anyone with the link''
2. In the settings, disable options for edit, download, etc.

Post writing:
1. If a paper, make sure to add ``research'' in categories as well.
