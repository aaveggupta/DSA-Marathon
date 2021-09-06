# DSA Marathon Community

Hey folks, My name is Aaveg, and I'm your DSA Marathon instructor! So, this is your final task, and you'll be learning how to contribute to open source. This isn't a typical repository with a list of plain text; instead, its more tends towards REAL-WORLD projects! Now let's see what you'll bring to the table!

## After doing below steps correctly you'll be see your name card on [this link](https://aaveggupta.github.io/DSA-Marathon/)

### Below Template is taken from, [First Contribution](https://github.com/firstcontributions/first-contributions).


#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-alonzo-church
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `index.html` file in a text editor,

1. Copy the below code and make necessary changes as It is indicated!

```
<div class="card">
      
      <!-- If you are female: change name of svg file to female
      If you are male: change name of svg file to male -->

      <img src="assets/imgs/male.svg" alt="" class="card__img">
      <div class="card__content">
        <div class="card__info">

          <!-- Type your name inplace of 'Your Name' -->
          <h2 class="card__name">Your Name</h2>

          <!-- Type the most dil se loving skill, jisko aap beintha seekhna chahte ho 😍 inplace of 'Your Interest' -->
          <span class="card__prof">Your Interest</span>
        </div>
        <div class="card__icons">
          <div class="card__icon-container-t">

            <!-- Paste your linkedin profile link in place of # -->
            <a href="#" target="_blank"><box-icon type='logo' name='linkedin' color='white'></box-icon></a>
          </div>
          <div class="card__icon-container-i">

            <!-- Paste your github profile link in place of # -->
            <a href="#" target="_blank"><box-icon name='github' type='logo' color='white'></box-icon></a>
          </div>
        </div>
      </div>
    </div>
  ```

  2. After making edits, paste the code in the ```index.html``` file, wherever it is mentioned to copy!

  3. Now save the ```index.html``` file and open it using browser! If your card is successfully created, Now Its the time to go to next otherwise debug it or share the problem in our [Discord Server](https://discord.gg/v6gQVhVG)!

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add index.html
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.


### HURRAY!! You have successfull made your contribution, Now just share this acheivement on your Socials and Don't forget to tag [me](https://linktr.ee/aaveg) and DSA Marathon Account!! 😍
#### Now  you'll be able to see your card on [this link](https://aaveggupta.github.io/DSA-Marathon/)