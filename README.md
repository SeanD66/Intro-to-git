# Intro-to-git
This repository contains basic introduction to git.

<h2>Name</h2>
Sean Daweng

<h2>Repository Overview : A brief description of this repository.</h2>
The purpose of this lab is to help students understand the fundamentals of
version control, learn the basic features of Git, and utilize GitHub for collaborative
development and project management.

<h2>Key Concepts: Importance of version control and Git features.</h2>
Version control is essential for managing changes to code, documents, and other files over time. It allows multiple people to collaborate on a project, track changes, and revert to previous versions if needed. Git, a popular version control system, offers several features that make it powerful and efficient.
<ul>  
Common Terminlogies:
  <li>Branching and Merging: Git allows you to create branches to work on different features or fixes independently.</li>
  <li>Distributed System: Unlike centralized version control systems, Git is distributed.</li>
  <li>Commit History: Git keeps a detailed history of all changes made to the repository.</li>
  <li>Staging Area: Git has a staging area where you can review and selectively commit changes.</li>
  <li>Collaboration: Git supports collaboration through platforms like GitHub, GitLab, and Bitbucket.</li>
</ul>
<h2>Instructions on cloning the repository and viewing the content.</h2>

 1) To clone the private repository from github into the local machine:
    <pre>git clone repository-URL/repository-SSH</pre>
    
 2) In order to view the content of the cloned repository. Go to the path where the repository is cloned(In my case it went to the Documents directory. It is where the code above was prompted.). We can type the list(ls) command to verify if the repository is cloned in the local terminal once the repository is cloned.

<h2> Git commands and their syntax, and functionality.</h2>
<table> <!--table start --> 
<tr> <!--row 1 start -->
 
<td width="33%">
Command
</td>
<td width="33%">
Syntax
</td>
<td width="33%">
Description
</td>

</tr> <!-- row 1 end --> 

<tr>
<td width="33%">
git clone
</td>

<td width="33%">
git clone URL or SSH
</td>

<td width="33%">
Clone a remote repository to local machine.
</td>

</tr> <!-- row 2 end -->

<tr> <!--row 3 start-->
<td width="33%">
git commit
</td>

<td width="33%">
git commit -m " "
</td> 

<td width="33%">
Commit changes with a message.
</td> 


</tr> <!--row 3 end-->

<tr> <!--row 4 start-->
<td width="33%">
git init
</td>

<td width="33%">
git init
</td>

<td witdth="33%">
Initializes Repository.
</td>
</tr> <!--row 4 end-->

<tr><!--row 5 start-->
<td width="33%">
git add
</td>

<td width="33%">
git add (file)
</td>

<td width="33%">
Add changes to the staging area.
</td>
</tr><!--row 5 end-->

<tr><!--row 6 start-->
<td width="33%">
git push
</td>

<td width="33%">
git push origin (branch-name)
</td>

<td width="33%">
Uploads changes to a remote repository.
</td>
</tr><!--row 6 end -->

<tr><!--row 7 start-->
<td width="33%">
git pull
</td>

<td width="33%">
git pull
</td>

<td width="33%">
Fetches and merges updates from remote.
</td>
</tr><!--row 7 end-->
</table> <!-- closes the table>
