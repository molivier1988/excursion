# Codecademy off-platform Excursion project

## Learning Outcomes
Practice using git when working on a project including:
- Add multiple changes to staging area
- Make commits after new feature added
- Push to GitHub repository

## Lessons Identified
I made a single (large) commit and push rather than adding small, incremental changes. Commiting smaller changes is best practice especially when collaborating with other developers as small changes
are easier to test and integrate.

## Workflow
Work on code => **add** changes to staging area  => **commit** changes => **push** to GitHub

## Commands used
`git add`                           => Adds changes to the staging area
`git status`                        => List changes waiting for commit
`git commit -m "Commit message"`    => Commits change (adds new **HEAD**)
`git log`                           => Displays **HEAD** of git
`git push -u main`                  => Pushes branch commits to GitHub repository

## References and Guides
[`Git Workflow`](https://www.git-scm.com/docs/gitworkflows)

[`git add`](https://www.git-scm.com/docs/git-add)

[`git commit`](https://www.git-scm.com/docs/git-commit)

[`git push`](https://www.git-scm.com/docs/git-push)

## Finally
When looking at structure and **responsiveness**, I tried CSS grid (1 column, 2 rows) but simplest method was to use **flexbox** and changing `flex-direction` to column. The page was instantly
responsive which was the desired effect.
