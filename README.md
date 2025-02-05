# Parent Repository for Git Subtree Testing

This repository was created to experiment with and test the functionality of Git subtrees. It serves as the **parent repository**, which means it will include and manage one or more sub-repositories using Git's subtree feature.

## Purpose
- Learn how to add and manage subtrees within a repository.
- Test pushing, pulling, and merging changes between the parent and subtree repositories.
- Understand best practices for working with subtrees in real-world projects.

## Usage
- Add a subtree: `git subtree add --prefix=subrepo <repository-url> <branch> --squash`
- Pull updates from subtree: `git subtree pull --prefix=subrepo <repository-url> <branch> --squash`
- Push updates to subtree: `git subtree push --prefix=subrepo <repository-url> <branch>`

## Notes
- This is purely a test repository, and changes here may not be production-ready.
- Feel free to experiment with subtree operations and track results.

Happy coding!

