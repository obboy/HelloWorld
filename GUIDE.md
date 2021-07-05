
# First Contributions


Our Community appreciates [firstcontribution](https://github.com/firstcontributions/first-contributions) community to support beginners. We are excited to add their steps here which we suggest to follow.

[firstcontribution](https://github.com/firstcontributions/first-contributions)  aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" src="assets/Fork.jpg" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/Clone.jpg" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/Copy_Url.jpg" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/HelloWorld.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the HelloWorld repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd HelloWorld
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-saadman-sayed
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m ":tada: introducing <your-github-username>"
```

replacing `<your-github-username>` with your github name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull-request.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/create-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

# 

## Acknowledgement
This steps are explained in another opensource community development project also known as [firstcontributions](https://github.com/firstcontributions/first-contributions). You can get more materials to learn from them. Go [visit](https://firstcontributions.github.io/#project-list) their github page and explore.  

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our discord team in case you need any help or have any questions. [Join discord team](https://discord.gg/cwAd9ey5).

Now let's get you started with contributing to other projects. They've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).
