# Create your commit message template file
## For example, create a file at ~/.gitmessage.txt:
```
vi ~/.gitmessage.txt
```
Add your desired template, e.g.:
```
# Title: Short summary (50 chars max)
# Description: Detailed explanation (wrap at 72 chars)
# Issue: Link or ID
```
*Save and exit~*

## Set it as your global Git commit message template:
```
git config --global commit.template ~/.gitmessage.txt
```
## Confirm it's set correctly:
```
git config --global --get commit.template
```
It should return:
```
/home/yourusername/.gitmessage.txt
```
