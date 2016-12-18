# Subversion, a Powerful Open-source Version Control System to Collect, Collaborate, and Integrate Your Work

*`CAHYANINGTYAS SEKAR WAHYUNI - 145150401111013`*

*`created on 12/18/2016 2:27:10 PM `*

> Subversion (SVN) is an open source version control system. Subversion is able to manage files and directories, and any changes made to them. This tool can operate across the networks which allows it to be used by people on different computers (Michael Pilato et al, 2008). So, based on this definition, SVN is a tool which help developers to integrate, collaborate, and controlling software that being developped. By using SVN, developers are able to save any development files in its repository.

> SVN Repository is similar to a folder or directory that may contain bunddle collection files. It is typically used to store all the files and directories that make up a single project or even collections of interrelated projects. SVN repository only records the changes or differences between files at each revision, called changeset. Changeset consists of a description of all the additions, modifications, and deletions to files within the project.

> SVN repository can be used to restore all files of a project to an earlier point. It will be useful if any bugs are detected in a new version and developers wish to revert back to the previous version. It can also be used to compare different revisions of a file(s). Moreover, it is possible to have multiple developers working on the same project. Each person can be assured they are working on the latest version of project files. It also allow for multiple versions of the same files to be maintained within one SVN repository. It is possible to quickly revert back to initiial version.

### SVN Life Cycle - How the Subversion Commands for Each Operation Work

 > **`1. Checkout`** 
        is used to create private workplace as working copy from repository             where developers do their changes and commit it after they finished. It would be impossible for any developers to make any changes before they checkout their project to create file copy in their own private workplace.

 > **`2. Update`**
        is used to update working copy and synchronize the working copy with the         repository. Repository is shared by all teams, and developers are able to          commit their changes.

 > **`3. Performing Changes`**
        is actions in which the developers are able to create, delete, or rename files. But these files have not been the part of the repository yet before they are being committed.

 > **`4. Revert`**
        is used to throw away any changes. Revert operation will cancel                 modifications that have been made to the working copy.

> **`5. Commit`**
         is used to apply changes from the working copy to the repository. This operations modifies the repository and other developers can see these changes by doing Update command.

### SVN Tutorial in Eclipse
To make it clear, I would like to share how SVN would be implemented especially on Eclipse. Here is the link on youtube for [SVN implementation tutorial in Eclipse](https://www.youtube.com/watch?v=Szgs3jmo2YU&feature=youtu.be) 


