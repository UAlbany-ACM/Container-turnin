# Container-turnin
A new assignment turnin system using containers

### Problem statement:

The current UAlbany turnin system is awful. It requires students to run/test their software on the SunOS 5.10 server, which is a huge inconvenience. We need to repeatedly `scp` the files, or use some third party tool.

### Solution Statement:

We can use containers. Containers allow us to package our applications, run them on our host OS, and ship them with the guarantee that it will run the same way on the graders OS.

### How we can accomplish this:

1) Host a container registry on a UAlbany a server. [Project Atomic Registry](http://www.projectatomic.io/registry/).

2) Mirror a stable version of a container platform for all desktop OS's (Linux/MacOS/Windows) for students/faculty to download.

3) Write documentation for how students can create custom container images, push them to the registry, and how graders (TA's/professors) can pull them for grading

4) Write scripts to automate this process

5) Work with faculty to get our system into use
