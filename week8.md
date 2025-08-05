# Week 8 - GitHub & WordPress Collaboration

## Learning Activities & Resources

Here are the resources I used to help me understand how to collaborate using GitHub and WordPress:

1. JCU lecture slides and recordings
2. GitHub official documentation
3. [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
4. Our group meeting and screen-sharing session

## Content Insights

Version control is essential in collaborative development. This week, we used Git and GitHub to manage our
WordPress theme project. We created a shared repository and each team member cloned it locally. By using branches,
commits, and pull requests, we could contribute our parts to the group work efficiently.

### Repository Setup

We pushed our existing WordPress theme folder into GitHub. A `.gitignore` file was added to exclude unnecessary or
sensitive files, such as '.ds_store' or IDEA files.

### Common Git Commands

| Command         | Purpose                                    |
|-----------------|--------------------------------------------|
| `git clone`     | Download a copy of the repo                |
| `git add`       | Stage file(s) for the next commit          |
| `git commit -m` | Save changes with a **m**eaningful message |
| `git push`      | Push local changes to GitHub               |
| `git pull`      | *Down*load the latest changes from GitHub  |

Team members are asked to fork the repository.
Also, we will use branches to avoid breaking the main version.
When a team member completed a task, they created a pull request so others could review and merge it.

## Career/Employability/Learning Insights

Version control tools like Git and GitHub are must-have skills in modern web development.
Almost every software company expects developers to be proficient in Git workflows.
This includes branching strategies, handling merge conflicts,
and keeping commits clean and meaningful.

In this group project, GitHub greatly improved our productivity.
It allows us to work in parallel, track changes, and review each other's code.
This is especially important for WordPress,
where files are intertwined — any mistake in a shared template could crash the site.

I had an question when I started building this project.
that was how to avoid pushing the entire WordPress folder to git, making the repo too big.
Later I learned to push only the theme folder.
This experience reminded me that in collaborative work,
a clean and minimal repo is more useful than a full local dump.

From this week, I also realised that understanding `.gitignore` is not optional.
Careless configuration could expose sensitive information or make the repo unusable for teammates.

As I plan for a career in web development,
I’ll keep refining my Git and GitHub skills — they’re more than tools;
they’re part of the team's communication.
