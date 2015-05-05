# LOLCompanion
LOLCompanion : LoL helper for Android

To get a working workspace :
```
cd <your_workspace>
git clone git@github.com:RynnHeldeD/LOLCompanion.git
```

You will now have a LOLCompanion folder in your workspace with two subfolders which may be *not* up to date.
Let's initialise the submodule for Git to know the two folders are two Git projects.
```
cd LOLCompanion/
git submodule init
```

Let's update the submodules to their latest version.
Launch this command from LOLCompanion folder every time you want to pull the latest commit of each module
```
git submodule update --remote
```

Congrats, your project is up to date and ready to work !
