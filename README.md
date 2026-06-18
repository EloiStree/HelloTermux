# HelloTermux
Info on Termux for Quest and Android for git


https://github.com/termux/termux-app/releases   
Download [termux-app_v0.119.0-beta.3+apt-android-7-github-debug_universal.apk](https://github.com/termux/termux-app/releases/download/v0.119.0-beta.3/termux-app_v0.119.0-beta.3+apt-android-7-github-debug_universal.apk)

```
pkg install git -y
pkg install gh
gh auth login
```

```
termux-setup-storage
cd ~/storage/shared
dir
cd ~/storage/shared/documents
```

```
git clone ...
``

```
git config --global --add safe.directory /storage/emulated/0/documents/CodeLabXR
```





```
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
```



