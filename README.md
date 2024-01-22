<h1>Lonux File Permissions Administartion</h1>

<h2>Description</h2>
At my organization, the research team contacted our security analysts and explained that they require certain document access to be changed to be in alignment with the correct authorization policies. Security of these documents and directories is crucial to maintaining operational integrity of the research and development department. The following steps were taken to accomplish this.
<br />

<h2>Languages and Utilities Used</h2>

- <b>BASH Scripting</b> 

<h2>Environments Used </h2>

- <b>Ubuntu VM within Coursera Lab Environment</b> 

<h2>Project walk-through:</h2>

<p>
I first entered the projects directory for the researchers using  <b>cd /home/researcher2/projects</b> and entered the command <b>ls -la</b> to display the files (including hidden files), directories and their permissions. 
 <br />
<img src="https://i.imgur.com/U2R7mIG.png" height="80%" width="80%" alt="Linux Administration"/>
<br />
<br />
I found that there is one directory called drafts and also a hidden file named .project_x.txt along with 5 other project txt files. Hidden files are identified by a period at the start of their name.
<hr>
The permissions for the files are explained through a ten character string at the beginning of the list, when I entered <b>ls -al</b>:
- The first character explains whether the file is a <b>directory (d)</b> or a <b>file (-)</b>.
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
