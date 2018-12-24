# git-alias
I'm sharing the git aliases I came up to use over time.

Index:
* [Git Alias?](#git-alias)
* [How to use](#how-to-use)
* [Example](#example)

## Git Alias
The term alias is synonymous with a shortcut. Alias creation is a common pattern found in other popular utilities like `bash` shell. Aliases are used to create shorter commands that map to longer commands. Aliases enable more efficient workflows by requiring fewer keystrokes to execute a command. (source)https://www.atlassian.com/git/tutorials/git-alias

## How to use

Either include the ```git-alias.txt``` or paste the content into your ```.gitconfig``` file.

```bash
curl -O https://raw.githubusercontent.com/git-alias/master/git-alias.txt
```
Edit your ```.gitconfig``` file and 

Either:
```
[include]
  path = git-alias.txt
```
Or:

Paste the contents of the file into your own ```.gitconfig``` file

## Example

One line logs with decorations
```olog = log --oneline --graph --decorate```
Add all
```aa = add --all```
Pull with rebase
```pr = pull --rebase```

