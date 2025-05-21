# Flattles Codebase 🛸

This is the organization dedicated to the code for Flattles. Below is the repository and a step-by-step on the different tools and software you may need to run each.

## Before You Get Started
### Git
For both projects, you will likely need to use git to easily handle code changes. On macOS and Linux, Git should already be installed in the terminal. On Windows, you can use the guide [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to install Git.

To clone a repository, there are two methods: With VSCode and with Git

With VSCode, log in to your GitHub by clicking the profile icon at the bottom of the left sidebar. Once you have signed in, you can then click the "Clone Git Repository" button on the Welcome page, or search for the function in the Search Bar. You will then be prompted to "Clone From GitHub", and when you click that, all the repositories your account has access to will appear. Simply click the repository you want to clone and the project will be copied to your computer at whatever location you specify, and the Git version control will be linked to it.

With just Git, first navigate to the repository on GitHub, and on the Code tab click the green Code dropdown. Copy the link on the HTTPS tab and open up a terminal instance. In your terminal, type the command `git clone [insert copied link]`. If this fails, it is likely due to not being signed in to GitHub in the terminal. GitHub has made it fairly annoying to set up, but it can be done following [this guide](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) and using extensive StackOverflow documentation.

**If you do not want version control** (aka you do not plan to push your changes to the repository in GitHub and will just make changes locally, then instead of copying the link on the HTTPS tab from GitHub, click "Download zip" from the same tab, and open the zip at whatever location you choose.

### NodeJS
For both the middleware and frontend, NodeJS is essential as it is the Javascript runtime both systems use, and allows us to use the CLI function `npm` to run each. To install it, navigate to [this website](https://nodejs.org/en) and download the latest version of NodeJS.

### Postgres
If you plan on working on or with the middleware, Postgres is essential. There are various ways to download and utilize Postgres based on your comfortability, whether that is using a CLI or GUI.
Follow the guide from the [official Postgres website](https://www.postgresql.org/download/) to download it and set it up for your system. To use it with the middleware, simply make sure that Postgres is running and your credentials are setup the same as the `env.json` file in the `flattles-middleware` repository.
