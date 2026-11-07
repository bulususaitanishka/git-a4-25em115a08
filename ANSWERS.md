# Assignment 4 - Answers

## 1. Difference between Fetch and Pull

- git fetch downloads changes from the remote repository but does not merge them.
- git pull downloads changes and merges them into the current branch.
We used fetch first to inspect the teammate's changes before merging.

## 2. Rejected Push

Error received:
! [rejected] main -> main (fetch first)
error: failed to push some refs

GitHub rejected the push because the remote repository contained changes that were not present locally.
Force-pushing is dangerous in team projects because it can overwrite other people's commits and cause data loss.

## 3. Origin, origin/main and -u

- origin: A nickname for the remote GitHub repository.
- origin/main: The main branch on the remote repository.
- -u: Sets the upstream branch so future push and pull commands can be used without specifying the remote and branch.

## 4. Lightweight and Annotated Tags

- Lightweight tag: A simple pointer to a commit.
- Annotated tag: Contains additional information such as the tagger, date and message.
Annotated tags are better for official releases because they provide more information and metadata.

## 5. Why use Pull Requests?

1. Pull Requests allow teammates to review and discuss code before merging.
2. They help identify mistakes and maintain code quality before changes enter the main branch.