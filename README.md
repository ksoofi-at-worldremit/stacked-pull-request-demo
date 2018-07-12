# stacked-pull-request-demo
This process would be really useful when working on features that are dependent on each other but should still be divided in separate pull requests for review.

1. Identify sub tasks to be done e.g. refactoring
1. Create a feature branch for first sub task suffix with task1, part1 or 1, use same convenstion when creating child branches, for the purpose of this guide I will call it subtask1
    1. Work on subtask1
    1. Commit your changes to subtask1
    1. Keep subtask1 updated from master
    1. Create a Pull Request from subtask1 to master
1. Create a new branch from subtask1 e.g. subtask2
    1. Work on subtask2
    1. Commit your changes to subtask2
    1. Keep subtask2 updated from subtask1
    1. Create a Pull Request from subtask2 to subtask1
1. Create a new branch from subtask2 e.g. subtask3
    1. Work on subtask3
    1. Commit your changes to subtask3
    1. Keep subtask3 updated from subtask2
    1. Create a Pull Request from subtask3 to subtask2
