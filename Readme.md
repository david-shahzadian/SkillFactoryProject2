**Skill Factory Module 2 Project**

###### Main info
Current repository public link is:
https://github.com/david-shahzadian/SkillFactoryProject2

###### Git flow:
master - main release code branch
dev (from master) - develop branch that includes developed and tested code
feature branch (from dev) - branch that includes a new feature code or bug fix code.

###### Scheme
master -> dev -> feature branch

###### Feature branch naming conventions.

Feature branch should include the Jira ticket name.
E.G. if ticket name is SF-102 then the branch name should be SF-102.
This is necessary for Jira to subscribe to commit, PR etc.

###### Feature merge process
Each branch should be merged to dev via Pull request approve.

###### Main git commands
To create a new branch use: _git branch {branch_name}_

To check out to the branch use: _git checkout {branch_name}_

To add file to git use: _git add {file_full_path_and_name}_

To make a commit use: _git commit -m {commit_notes}_

To push changes use: _git push_
