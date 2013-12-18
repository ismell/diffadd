== Git diffadd ==

git diffadd is a GUI alternative to `git add -p`. It allows you to pick and choose parts
of a file to add.

Add diffadd to your path and then add the following to your .gitconfig

    [alias]
      diffadd = "!cd \"$GIT_PREFIX\"; diffadd"


Then you can do `git diffadd`

This has been tested using https://sourcegear.com/diffmerge/ 
