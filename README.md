# Android-Application-Tutorials-Examples
Complete Android Application training program on this examples http://www.larnr.com/courses/android-apps-development 

This repo contains about seventy source code examples from the recipes published in the Larnr Education's Android Development Training(see http://www.larnr.com/courses/android-apps-development), a great source of tutorial material for the Android Developer. Not all recipes in the book or online have code accompanying them; this repo features code that was either linked by the contributor, or in a few cases, re-constructed as a New Project by the editor, for your convenience.

Further note that not all programs used in the book/online appear here; some of the examples in the book/online are only program fragments taken from other programs that can’t be included. And of course some projects used as examples in the book/online are routinely hosted elsewhere.

Each Directory comprises its own Eclipse project, and has a name that is cited at the end of the corresponding Recipe, under the "Source Code Download" section. If you open the repo in Eclipse with eGit, be sure to check the "create all projects" checkbox. If you want to keep these mini-projects separate from your "regular" work, you may want to use the Git repo as an Eclipse workspace (use File→Switch Workspace→Other→Browse). The .metadata directory is already in .gitignore.

Obviously the Googlezilla has spoken and we will have to migrate kicking and screaming to Android Studio and Gradle; pull requests for this would also be welcomed.

You can download this as a Zip file, but then you won’t get updates, and it will be hard to collaborate with the Editor and other contributors. If you’re new to Git, see the page on GitHub about how to collaborate. You can either send diff/patch files or, if you forked your own copy, send a pull request. Remember that GitHub is a free service for public projects!

If you open the repo as an Eclipse Workspace and no projects appear, despair not! Just do File→Import…→General→Existing Projects Into Workspace, browse to the top of the repo (the list of projects should appear), be sure "Import projects into workspace" is NOT checked, and click Finish; wait a bit.

Many of the projects may (depending on your version of Eclipse) give you some noise when you first open them due to bin and/or gen being missing. The Eclipse plug-in will usually create them but not notify that it’s done so, meaning you just have to do Refresh (F5), failing that, close and re-open the project. Does not happen with current Eclipse, last I tried.
