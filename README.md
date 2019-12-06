# UWRFChatBot

This is the page that will describe our teams Git workflow strategy.

In general, we will follow the first workflow found on this page
https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf

The workflow will work as follows

we keep our working code that is tested and bug free in our MASTER branch.

At the start of a sprint, we will make a branch off of MASTER called DEVELOP

we put features, bug fixes, and other additions that are completed during a sprint
in our DEVELOP branch

team members will create branches off DEVELOP to add code, make changes, or test locally.

When team members are satisfied with their code and have tested it locally, they will push
their changes into DEVELOP

At the end of the sprint, we make sure our DEVELOP branch works as intended and merge DEVELOP
branch into our MASTER branch. this is the only time anything is merged into MASTER

