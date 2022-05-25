# Practice Cloning a Repository from Github

## Directions

### Part 1 - Fork & Clone the project

* Begin by _forking_ this project into a personal repository.
  * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the _newly forked repository_.
* Use the `git clone` command to clone the repository from **your account** into the directory on your computer that you use to keep your projects (ex. `dev-projects` directory).


### Part 2 - Edit the _cloned_ project

* `cd` into the `root directory` of your new cloned repository

* Use your `command line` to add a simple file structure:
	- Add a new file called `index.html`using the `touch` command
	- Add a new folder called `assets` using the `mkdir` command
	- Add a new folder `inside of the assets folder` called `css` -- you'll have to `cd` into the `assets` folder, and then use the `mkdir` command
	- Within the `css folder`, add a file called `style.css`

### Part 3 - _Pushing_ new changes to repository

* From a _terminal_ navigate back to the `root` directory of the _cloned_ project.
* From the root directory of the project, execute the following commands:
  * `git add .`
    * Add all files in current directory to the staging area
  * `git commit -m 'Add file structure'`
    * Save all staged changes to local repository
  * `git push`
    * Push changes from local repository to remote repository
  * Go back to your Github Profile, navigate to your forked version of the project, refresh the page & you should see the changes you made to the file structure
