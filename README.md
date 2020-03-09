####Git Operations
#1.create team account<br/>
We created a team account in which the name is demo.</br>
#2. Create empty repository in any git remote repository service and add
collaborators.
In this demo group,we added a three collaborataters-Anjali venugopal,Revathychandran and Rahul Ramakrishnan</br>
#3. Leader must create the first commit
In this team,the team leader created the first commit</br>
commit is perform by the command  - git commit -m "commit msg"
#4.All members must clone the remote repository
After the first commit by leader,all the team members clone the remote repository.Pushing a file to the remote repository  without clone will raise an error.<br/>
clone is perform by the command   -git clone https://github.com/Anjali-941/demo.git gitfolder
#5.Each member must create a feature brach each and add features to
them(any mod)
After cloning the remote repository,all the members in my group  created a branch and added files to that branch.<br/>
New branch is created by the command  -git checkout -b pree.<br/>We can view can all the branch by the command  - git branch
#6.Commit changes to branches.
Here we modify an existing file in our branch and commit that file to the new branch</br>
#7.Push the branches.
Here i push the files to the new branch using the command  - git push --set-upstream https://github.com/Anjali-941/demo.git pree
#8. View Graph.
To visualize our git repository,we can use the graph.The command used for this is  -  git log --all --decorate --oneline --graph
#9. Leader must make changes to the master.
Team leader can change the committed file in the master branch.
#10.All member must rebase their branches to the position of latest commit in
master.
Rebase is another method for ingrating changes from one branch to another.
