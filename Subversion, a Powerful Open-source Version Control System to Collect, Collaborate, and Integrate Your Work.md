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

### How did technically SVN works in Eclipse would be explained by these pictures as follow :

- Open your eclipse

![enter image description here](https://lh3.googleusercontent.com/-N9eHdKPkeBw/WFdIpjkunLI/AAAAAAAAAHM/B8ILU-KNKoYgjHXDEWGj4-xthFR8naIHQCLcB/s1000/TAMPILAN+ECLIPSE.PNG "TAMPILAN ECLIPSE.PNG")

- Click SVN Repository Exploring, then new, repository location
![enter image description here](https://lh3.googleusercontent.com/-hPgUsA2k1xE/WFdIw2aPaVI/AAAAAAAAAHU/hG9Tfqm2X5QaVuCoBrTiFtwS0KlRhkIyQCLcB/s1000/SVN+REPOSITORY+EXPLORING.PNG "SVN REPOSITORY EXPLORING.PNG")

- Enter the URL to connect to repository, then click finish
![enter image description here](https://lh3.googleusercontent.com/-PbrdPQT6sCs/WFdJEtAPLeI/AAAAAAAAAHk/qARCRkVuHFUsLKYE0o5tyHQvwZ90AHK4gCLcB/s1000/REPOSITORY+URL+TO+CONNECT+TO+REPOSITORY.PNG "REPOSITORY URL TO CONNECT TO REPOSITORY.PNG")

- Repository would be added to your eclipse
![enter image description here](https://lh3.googleusercontent.com/-3e2L4BoS4XQ/WFdJSf08JkI/AAAAAAAAAHs/I-2HGgWBtRUjwJxUk9TS-rzqbc3aXi7RACLcB/s1000/REPOSITORY+ADDED.PNG "REPOSITORY ADDED.PNG")

- this repository consist of trunks, branches, and tags. click branches.
![enter image description here](https://lh3.googleusercontent.com/-1INs77ZbF2I/WFdJeXnRQmI/AAAAAAAAAH0/DXTpOWRw8G8DzdWYLH-jf_sQ87X_zmm6QCLcB/s1000/TRUNKS%252C+BRANCHES%252C+TAGS.PNG "TRUNKS, BRANCHES, TAGS.PNG")

- you will see many projects stored in repository
![enter image description here](https://lh3.googleusercontent.com/-Zk8tyPPK7yc/WFdJjyR2t2I/AAAAAAAAAIA/oISRWE1LlyQDFBrV6ImObT41aP9pMBRuQCLcB/s1000/PROJECTS+STORED+IN+REPOSITORY.PNG "PROJECTS STORED IN REPOSITORY.PNG")

- do checkout command to creat file copy on your local computer. please be noticed that developers would not be able to do editing before it being checked-out
![enter image description here](https://lh3.googleusercontent.com/-A21OS6BK090/WFdJon1eCII/AAAAAAAAAII/QYBqehfvKhcjGb02TuYc8yh7PeHY5kkGwCLcB/s1000/CHECK+OUT+PROCESS.PNG "CHECK OUT PROCESS.PNG")

- after developers checked-out project, they can modify anything.
![enter image description here](https://lh3.googleusercontent.com/-pAOaneUv7dk/WFdJvjcExgI/AAAAAAAAAIQ/98j_eoC37sU70b20FuOfWagtkRQqL5EUgCLcB/s1000/MODIFYING+FILE+IN+TAB+JAVA.PNG "MODIFYING FILE IN TAB JAVA.PNG")

- after you finished modifying, if you saved this project, it would be stored only in local computer.
![enter image description here](https://lh3.googleusercontent.com/-YonmWuL5jIs/WFdJ0zyBHTI/AAAAAAAAAIY/200Wupt4NkgE__t9vbDwzidZHDJZV8G4QCLcB/s1000/SAVED+THAT+ONLY+AVAILABLE+IN+LOCAL+COMPUTER+ONLY+UNCOMMITTED.PNG "SAVED THAT ONLY AVAILABLE IN LOCAL COMPUTER ONLY UNCOMMITTED.PNG")

- you need to synchronized this project with SVN repository to keep update with other developers.
![enter image description here](https://lh3.googleusercontent.com/-SP76nsRyNnM/WFdJ57nRprI/AAAAAAAAAIg/cH3dz0PBzEszBiDoBPTHKZzSvCh2DnPEwCLcB/s1000/SYNCHRONIZE+WITH+SVN+REPOSITORY.PNG "SYNCHRONIZE WITH SVN REPOSITORY.PNG")

- after it being synchronized, the incoming and outgoing changes are viewed.
![enter image description here](https://lh3.googleusercontent.com/-eruXFp8ERvA/WFdJ-oIxM7I/AAAAAAAAAIo/jfTwVduBFEQwgfbpk2A8DB7Sqv7LCvV8ACLcB/s1000/AFTER+BEING+SYNCHRONIZED%252C+THE+INCOMING+AND+OUTGOING+CHANGES+ARE+VIEWED.PNG "AFTER BEING SYNCHRONIZED, THE INCOMING AND OUTGOING CHANGES ARE VIEWED.PNG")

- if you double clicked the modified file, you will see any comparison before edited and after edited.
![enter image description here](https://lh3.googleusercontent.com/-dAil7q1qtvU/WFdKZxXM8KI/AAAAAAAAAJE/Lhp21NArtf0Hb_SOAi3VXiTgLhw_oKzpQCLcB/s1000/DOUBLE+CLICK+THE+MODIFIED+FILE.PNG "DOUBLE CLICK THE MODIFIED FILE.PNG")

- displaying the changes in special comparing view
![enter image description here](https://lh3.googleusercontent.com/-eCvYoRDZqJI/WFdKkgUdcEI/AAAAAAAAAJQ/8HoqSiQeCmovNzV3DNhl7d-lliQxxHQsgCLcB/s1000/DISPLAY+THE+CHANGES+IN+SPECIAL+COMPARE+VIEW.PNG "DISPLAY THE CHANGES IN SPECIAL COMPARE VIEW.PNG")

- developers might take revert action to cancel changes, or commit action to push to SVN server.
![enter image description here](https://lh3.googleusercontent.com/-8HnoWiF88Y4/WFdKpeRdiTI/AAAAAAAAAJY/aPv4GFHra74IoBecSNYsu-5hFlY5t1s8ACLcB/s1000/ACTION+TAKEN+AFTER+DOUBLE+CLICK.+REVERT+OR+COMMIT+TO+PUSH+TO+SVN+SERVER.PNG "ACTION TAKEN AFTER DOUBLE CLICK. REVERT OR COMMIT TO PUSH TO SVN SERVER.PNG")

- developers shoud update their SVN to keep up-to-date with any changes made by other developers.
![enter image description here](https://lh3.googleusercontent.com/--aKGxsscN8M/WFdKt0-eoBI/AAAAAAAAAJs/tEoSol1tLqAuE0V2qoFx-IGDT9b8UTnvwCLcB/s1000/UPDATE.PNG "UPDATE.PNG")


*`That's 15 simple steps to use SVN in Eclipse`*
