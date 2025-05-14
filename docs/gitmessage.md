# Create your commit message template file
1. For example, create a file at ~/.gitmessage.txt:
```
vi ~/.gitmessage.txt
```
Add your desired template, e.g.:
```
# Title: Short summary (50 chars max)

# Description: Detailed explanation (wrap at 72 chars)

# Issue: Link or ID
```
Save and exit 

2. Set it as your global Git commit message template:
```
git config --global commit.template ~/.gitmessage.txt
```
3. Confirm it's set correctly:
```
git config --global --get commit.template
```
It should return:
```
/home/yourusername/.gitmessage.txt
```
Result:
Now every time you run git commit (without -m), your editor will open with this template pre-filled.

Let me know if you want an example tailored to a specific use case (like bug tracking, feature development, etc).