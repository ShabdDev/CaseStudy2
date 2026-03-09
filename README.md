CaseStudy2 

Problem Statement: You work for Zendrix Software & Co. You have been assigned the task of updating the master branch of their Git repository with all the features from the feature branches. 

Following is the GitHub account: https://github.com/devops-intellipaat/merge-conflict.git 

Consider: 
● Feature1 branch to be a public branch 
● Feature2 branch to be a private branch 

The company relies on a monolithic architecture and for now all the code resides in one file “main.c”. 
The respective features have been added in the feature branches for main.c. 
Meanwhile, a security patch was made to the master branch, and now feature1 and feature2 branches are behind from master by 1 commit. 

Tasks To Be Performed: 
1. Update Feature1 and Feature2 branch with the Security Patch 
2. Apply changes of Feature1 and Feature2 branches on master 
3. Finally push all the branches to GitHub For solving this, 
please fork the repository to your GitHub account and then work. As a solution, please submit your GitHub’s repository link.

solution
1.  git clone https://github.com/ShabdDev/CaseStudy2.git
2.  cd CaseStudy2
3.  git log
4.  git branch
5.  git branch -a
6.  git checkout feature1
7.  git merge master
8.  nano main.c
9.  git add main.c
10. git commit -m "security patch is added in main.c in feature1 branch"
11. git checkout feature2
12. nano main.c
13. git merge master
14. nano main.c
15. nano main.c
16. git add main.c
17. git commit -m "security patch is added in main.c in feature2 branch"
18. git checkout master
19. git merge feature1
20. nano main.c
21. git merge feature2
22. nano main.c
23. git add main.c
24. git commit -m "main.c is updated with branch feature2 and branch feature1 logic in master branch"
25. git branch
26. git push origin master
27. git log
28. git push origin feature1
29. git push origin feature2
30. history
