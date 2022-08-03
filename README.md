# code-shell
For attaching tmux to vs code


Hello,

After following this post,https://medium.com/@jeanmark.wright/making-vs-code-and-tmux-awesome-9938081b9c25 
I came to a conclusion that nvim, tmux and vscode could work together on MacOS

Here is the script. The steps to configure are:

* Open terminal or iterm2
* Setup tmux (refer my .tmux repo)
* Then
```
$ cp https://github.com/abhishek0010/code-shell/blob/main/code-shell /usr/local/bin/.
$ sudo chmod 755 /usr/local/bin/code-shell
```
* Open VS code-> settings.json
* Add
```
"terminal.integrated.shell.osx": "/usr/local/bin/code-shell",
```

Thats it.
