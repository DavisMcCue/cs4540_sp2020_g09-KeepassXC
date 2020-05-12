# KeepassXC
KeepassXC is a password manager, software designed to conveniently and securely store a user's account logins. Credentials are stored in an encrypted database file, denoted by a .kdbx extension. Passwords can be added manually or imported from other formats such as csv, and can then be sorted and organized. KeepassXC includes additional features such as random password generation, login auto-type, web browser integration, and utilities for merging password databases.

# Organization
## Qt
KeepassXC is written in C++ using the Qt framework. Qt is a cross-platform application framework that provides the widgets used for the GUI.  
Some important Qt concepts:  
#### Widget Inheritance

#### Signals and Slots

## KeepassXC
The source code is organized fairly intuitively:  
* The 'core' directory contains essential components.  
* 'cli' and 'gui' contain the command line interface and graphical interface, respectively.  
* Other features, such as autoytpe and browser integration, are in their own directories.  

# Development Process

From CONTRIBUTING.md:  

> The Branch Strategy is based on git-flow-lite.  
> * master – points to the latest public release  
> * develop – points to the development of the next release, contains tested and reviewed code  
> * feature/\[name\] – points to a branch with a new feature, one which is candidate for merge into develop (subject to rebase)  
> * hotfix/\[name\] – points to a branch with a fix for a particular issue ID  
