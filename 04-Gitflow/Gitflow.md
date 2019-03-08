## Build Week Git Workflow

The Lambda Standard Git workflow is to be used as your version control for this project. 

Your Team Leader will set up a Github organization for you to join. Each organization should have a **SEPARATE REPOSITORY** for each student's role (e.g. Landing Page (UX/UI), Frontend, Backend).

Here is a link to documentation on Github Organizations: [https://help.github.com/en/articles/about-organizations](https://help.github.com/en/articles/about-organizations)

Here is an example of what we're going for with the Github Organization: [https://github.com/coordinator-storytelling](https://github.com/coordinator-storytelling)

EU Students will work with the following Git Flow however, there will be no need for Github Orgs*

**The Build Weeks Git Work Flow**

- **The only difference from the Lambda Git Flow is that you won't be using "Forks" for development.**
- You will all have your OWN Repo that will live in your Github Org that you will work from.
    - If you are working together with another Front End Architect you will both work on the same repo on separate branches.
- Clone the master branch of the repository.
- Work will be done on your typical 'firstname-lastname' branch.
- All branches will be merged back into the master branch.
- Remember to add your Team Leader or PM as a collaborator on the project.  NO FORKS. Keep it simple.

    ### A possible solution to merge conflicts

    **On your branch currently:** 

    `git checkout master`

    `git pull`

    `git checkout your-branch`

    `git merge master`

    Resolve Merge conflicts.

    - This isn't very intuitive. You'll usually be prompted by a `vim` prompt in your command line. Use your Team Lead to help resolve the conflict.

    `git commit -m 'conflicts resolved'`
    Now you have master in your branch and are in sync.