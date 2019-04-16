# git_remote_push_test
repo for testing merge conflicts between remote and local

I am testing the merge conflicts that can arise between remote and local branches.

Scenario 1 - If remote has made some changes to a file and local also makes changes in the same lines of the file, then
If we push from remote, what needs to be done?

Scenario 2 - If remote has made some changes to a file and local also makes changes in the same lines of the file, then
If we push to remote, what needs to be done?

For further details, see file.txt. It contains my procedure, observations and understanding about merge conflicts and detailed description of above scenario.

I am editing this file and creating a new branch on remote, then going to make a pull request.
***
# Things to check in future-
1. Local only - when some  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**a) unstaged** \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**b) staged** \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;changes are present in a branch, then what happens on  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i) **_creating a new branch_** or  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii) **_doing a checkout to existing branch_**  
&nbsp;&nbsp;&nbsp;**Total 4 cases are there in above scenario**  
&nbsp;&nbsp;&nbsp;**To be checked-**  
&nbsp;&nbsp;&nbsp;&nbsp;Do the changes carry forward to that branch or not?  
&nbsp;&nbsp;&nbsp;&nbsp;Also, what if the file was staged in a commit and then branch was switched?               
