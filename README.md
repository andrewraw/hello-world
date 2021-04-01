# hello-world
Just a repository
Hi,

 All people who look for a designed place in the exo-care of earth. Dont fight for things, let thing come to you, whatever comes to you.
 # Errors
 
 nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git pull android-work origin
fatal: 'android-work' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git push --help

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git remote add Android D:\Andrew\Android\.git

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git push -u Android master
fatal: 'D:AndrewAndroid.git' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git push -u origin master
To https://github.com/andrewraw/android-work.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andrewraw/android-work.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git remote add Android https://github.com/andrewraw/android-work.git
fatal: remote Android already exists.

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
$ git pull origin
You asked to pull from the remote 'origin', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.

nitwi@DESKTOP-AKUBDQB MINGW64 /d/Andrew/Android (master)
