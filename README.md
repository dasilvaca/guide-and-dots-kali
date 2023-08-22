# What about this repo?

This repository contains the most interesting packages I use to my daily work on linux. For now. I am using kali-linux. But, I'll try to find packages available on every common repositories and major platforms. Like Arch, Debian, Ubuntu, Fedora, etc. (My philosophy is: if it's available for Debian, it must be available for the others. With the exception of Arch, of course, but, it's probably that them could be available for Arch too).

## Why?

Well, because when I was a newbie on linux, I had a lot of problems to find the best packages to my daily work. I had to search a lot of time to find the best packages for my needs. And, I had to install a lot of packages to find the best ones. So, I decided to create this repository to help the newbies on linux. And, to help the oldies too. I hope this repository could help you too.

Also, because when I will migrate to another distro, I would like to keep my favorite packages and their cofigurations.

## Interesting packages

Here I will list the packages I use by category.

### General

### Window managers, compositors and things I use to customize them

- [i3wm](https://i3wm.org/): A tiling window manager. I use it because it's very customizable and it's very fast.
- [Dunst](https://dunst-project.org/): A notification daemon. I use it to display my notifications.

### Shells and terminals

- [Terminator](https://terminator-gtk3.readthedocs.io/en/latest/): A terminal emulator. I use it because I can get a personalized color palette I made on terminal.sexy... It has some feutures as multitab, split screen, etc.
- [Zsh](https://www.zsh.org/): A shell. I prefer it over bash because itś more customizable and faster. I use it to run my scripts and to run my servers.
- [Oh-my-zsh](https://ohmyz.sh/): A framework for zsh. Itś highly customizable and still fast fast. It has extensions as auto-completion, syntax highlighting, etc.

### Text editors

- [Neovim](https://neovim.io/): A light text editor, used mainly on CLI, it's very customizable and it's very fast. I use it to write my scripts when I need to take a fast note, or to practice my vim skills and fast coding without any extre feautures. I need to learn more of it and which plugins are the best for me.
- [VSCode](https://code.visualstudio.com/): A text editor with lots of available plugins and formatters that seems useful.I use it when I need to debug or develop a large project, is the best tool I have. I am thinking in list the plugins I use... But maybe later. The installation of this text editor is tricky. I had to add it repository to my source.list and then install it.

### IDEs

- [intellij-idea-ultimate](https://www.jetbrains.com/idea/): A IDE for java. I use it to develop java applications. I am thinking in list the plugins I use... But maybe later. The installation of this text editor is tricky. I had to add it repository to my source.list and then install it.
- [android-studio](https://developer.android.com/studio): A IDE for android. I use it to develop android applications. I am thinking in list the plugins I use... But maybe later. The installation of this text editor is tricky. I had to add it repository to my source.list and then install it.

### Package Managers

- [Aptitude](https://wiki.debian.org/Aptitude): A package manager. I use it to install and remove packages. I prefer it over apt-get because it's more user friendly and suggest better some quick fixes.
- [Git](https://git-scm.com/): A version control system. I use it all the time.
- [Pip](https://pypi.org/project/pip/): A package manager for python. I use it to install and remove python packages.
- [SDKMAN!](https://sdkman.io/): A package manager for almost any SDks!.
- [Maven](https://maven.apache.org/): A build automation tool. I use it to build my java applications.
- [Gradle](https://gradle.org/): A build automation tool. I use it to build my java applications.

### Tools, compilers, interpreters and file managers on CLI

- Tree: A command line tool to display the directory structure of a path as a tree.
- [ranger](https://ranger.github.io/): A CLI file manager. I use it to manage my files on the go.

### Tools, filemanagers and apps on GUI

- [Thunar](https://docs.xfce.org/xfce/thunar/start): A file manager. I use it to manage my files on the go.

- Compton: A compositor for X. I use it to make my windows transparent.
- [Brave](https://brave.com/): A chromium based web browser. Itś fast, seems secure, is open source and I trust in it. Is my favorite web browser.

### Phorenics and cibersecurity toolbox

- [exiftool](https://exiftool.org/): Read and write meta information in a wide variety of files. Essential to know more about a file metadata.
- [nmap](https://nmap.org/): The Network Mapper. A free and open source utility for network discovery and security auditing. Essential to know more about a network, such uas the pots that a server has openned and how them are used for.

### Virtualization and containers

- [Docker](https://www.docker.com/): A container platform. I use it to run my servers and to run my applications on a container. Docker Engine is required, but I also use Docker Desktop.
- [Kubernetes](https://kubernetes.io/): A container orchestration platform. I use it to manage my containers. I use kubernetes on docker desktop.
- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/): A command line tool for kubernetes. I use it to manage my containers on the go. It's required to use kubernetes on cli.
- [gcloud cli](https://cloud.google.com/sdk/docs/install): A command line tool for google cloud.
- [kvm](https://www.linux-kvm.org/page/Main_Page): A virtualization platform. I use it to run my virtual machines.
- [virt-manager](https://virt-manager.org/): A virtual machine manager. I use it to manage my virtual machines.
- [QEMU](https://www.qemu.org/): A virtualization platform. I use it to run my virtual machines.
- [ovirt](https://www.ovirt.org/): A virtualization platform. I use it to run my virtual machines.

### Programming languages

- [Python](https://www.python.org/): A programming language. I use it to develop my scripts and to develop my servers.
- [Java](https://www.java.com/): A programming language. I use it to develop my servers. I use the Oracle SDK 20.
- [C++ (G++)](https://www.cplusplus.com/): A programming language. I use it to develop my servers. I prefer G++.
- [Javascript](https://www.javascript.com/): A programming language. I use it to develop on front-end solutions.
- [Dart](https://dart.dev/): A programming language. I use it to develop my mobile applications.
- [Kotlin](https://kotlinlang.org/): A programming language. I use it to develop my mobile applications.
- [Go](https://golang.org/): A programming language. I use it to develop my servers.
- [Rust](https://www.rust-lang.org/): A programming language. I use it to develop my servers.
- [OpenCL](https://www.khronos.org/opencl/): A programming language. I use it to develop graphics applications.

### Programming languages tools

- [Maven](https://maven.apache.org/): A build automation tool. I use it to build my java applications.
- [Gradle](https://gradle.org/): A build automation tool. I use it to build my java applications.
- [Node.js](https://nodejs.org/en/): A javascript runtime. I use it to run my javascript applications.
- [npm](https://www.npmjs.com/): A package manager for javascript. I use it to install and remove javascript packages.

### Programming languages frameworks

- [Spring](https://spring.io/): A java framework. I use it to develop my servers.
- [Hibernate](https://hibernate.org/): A java framework. I use it to develop my servers.
- [JPA](https://www.oracle.com/java/technologies/persistence-jsp.html): A java framework. I use it to develop my servers.
- [Django](https://www.djangoproject.com/): A python framework. I use it to develop my servers.
- [Angular](https://angular.io/): A javascript framework. I use it to develop my front-end solutions.
- [Flutter](https://flutter.dev/): A framework for cross-platform development. I use it to develop my mobile applications.

### Programming languages libraries

- [Pandas](https://pandas.pydata.org/): A python library. I use it to manipulate my data.
- [Numpy](https://numpy.org/): A python library. I use it to manipulate my data.
- [Matplotlib](https://matplotlib.org/): A python library. I use it to plot my data.
- [Pillow](https://pillow.readthedocs.io/en/stable/): A python library. I use it to manipulate my images.
- [Scikit-learn](https://scikit-learn.org/stable/): A python library. I use it to manipulate my data.
- [Tensorflow](https://www.tensorflow.org/): A python library. I use it to manipulate my data.
- [Keras](https://keras.io/): A python library. I use it to manipulate my data.
- [OpenCV](https://opencv.org/): A C++ library. I use it to manipulate my images.
- [P5.js](https://p5js.org/): A javascript library. I use it to manipulate my data.
- [React](https://reactjs.org/): A javascript library. I use it to manipulate my data.
- [React Native](https://reactnative.dev/): A javascript library. I use it to manipulate my data.
- [JQuery](https://jquery.com/): A javascript library. I use it to manipulate my data.

### Databases and database managers

- [MySQL](https://www.mysql.com/): A relational database management system. I use it to store my data while developing my applications.
- [MongoDB](https://www.mongodb.com/): A document-oriented database. I use it to store my data in my applications.
- [DBeaver](https://dbeaver.io/): A database manager. I use it to manage my databases.

### Multimedia

- [VLC](https://www.videolan.org/vlc/index.html): A multimedia player. I use it to play my videos and music.
- [Cheese](https://wiki.gnome.org/Apps/Cheese): A webcam application. I use it to take photos and record videos with my webcam.
- [OBStudio](https://obsproject.com/): A screen recorder. I use it to record my screen.
- [Audacity](https://www.audacityteam.org/): A audio editor. I use it to edit my audios.
- [Lorien](https://github.com/mbrlabs/Lorien.git): Lorien is an infinite canvas drawing/note-taking app that is focused on performance, small savefiles and simplicity. I use it to take notes and to draw.
- [Notion](https://www.notion.so/): A note-taking web application. I use it to take notes.
- [Document Viewer](https://wiki.gnome.org/Apps/Evince): A document viewer. I use it to read my documents.

### Servers

- [Wildfly](https://www.wildfly.org/): A server. I use it to run my java applications. I'm learning to using jakarta ee.

### Servers tools

- [Postman](https://www.postman.com/): A API client. I use it to test my APIs.
