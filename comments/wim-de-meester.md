# Comments on the IT training

## Part one: Linux System administration

+ Very nice overview and easy to follow (for me).
+ Maybe it was not entirely clear for some people why they need these commands / scripts.
+ I learned a few extra things.
+ I already wrote a lot of extra module files on my Mac this morning. However, module on the mac uses lua files. I could not use the examples given in the tutorial on my Mac.

## Part two: Git and GitHub

+ Also a very nice overview.
+ I already installed the git tab-completion file.
+ The explained git-flow does not work perfectly in larger projects, when the pull-requests are not automatically accepted. I'll try to explain why and what to do in larger projects. The first part is the same as explained during the training:
  + Fork the repository.
  + Clone the forked repository.
  + Make a new branch.
  + Do the changes, add new files and commit the changes.
  + DO NOT MERGE! But push the branch to your remote repository.
  + Do a Pull Request from the branch of your remote repository to IvS-KULeuven/git-crash-course on GitHub.
  + The advantage of this method is that when the Pull Request is not accepted immediately (because some extra changes are needed), you will only need to push your changes to the same branch and the Pull Request will be automatically adapted to include the latests changes. This will not work if you merged first locally to your master branch (well, it will work, but you cannot continue with your development as long as the Pull Request is not accepted).
+ The previous point was only for your information, it would have been way to complex to explain this during the training.
+ I'll push my branch and open a Pull Request from this branch.
