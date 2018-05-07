# Package Linux-scripts-bootstraps

- [CopyRight ©](#CopyRight)
- [Repository](#Repository)
- [About](#About)
- [Installation](#Installation)
- [Contents](#Contents)
- [Running the Package](#Running)
- [About the Author](#About-the-Author)
#
### CopyRight ©  **Install at your own Risk
- This program is free for re-distribution provided this copyright header is left in place.  
- There is no warranty or guaranty of any kind in any way and is not assured to be as required and may not work exactly as designed for all os systems operating various potential conflicting software.  
- It is recommended to read the contents of the scripts to be assured of the installation process and what will be installed. 
- The user is free to modify the code as required. 
- There may not be an associated uninstalling script, so uninstalling is the owners responsibility.
- It is recommended to be installed on a test system in a test environment before promoting to a production environment.
#
### Repository
- https://github.com/RMelanson/linux-scripts-bootstraps.git
#
### About
- Version: 1.0.0
- Release Date: May 06 2018
- Purpose: Bootstraps is a simplified installation package for many Linux packages.
- Description: Bootstraps is a master bootstrap utility for downloading and installing various software bootstraps for software initialization on Linux. Bootstraps may be installed as a bootstrap or after the Linux system has been launched. 
- The masterBootstrap.sh is used to download all the bootstraps from the git repository for future potential installation.
#
### Installation
- Execute the masterBootstrap.sh*, upon installation of a new Linux installation as a bootstrap or as a stand alone bash script. If executing the script manually on a Linux O.S. after downloading from the git repository, be sure to:
  - execute as root ./masterBootstrap.sh
  - or as user with sudo access sudo ./masterBootstrap.sh
- *Notes: 
    - All script packages are installed under /tmp/scripts directory and may be analyzed in that directory.
    - You may modify the script installation file (??...??Bootstrap.sh) to change the directory package installation location.
    - Upon Completion of installation, the installation directory and all contents may be removed.
#
### Contents 

- README.md ~ Readme file
- masterBootstrap.sh  ~ Installs this package
- devToolsBootstrap.sh ~ Installs standard Linux development components.  Read the script and comment out those components you may not want installed.
- stockWidgetsBootStrap.sh ~ Installs Java Rest API's Propritary software for Stock analysis to JBOSS. (WIP**)
- jbossBootstrap.sh ~ Installs JBOSS wildfly community edition with complete access as admin.
- mySqlInstall.sh ~ Installs Mysql
- s3fsBootstrap.sh ~ Installs Amazon Web Services S3 File system to mount S3 as network drives on the linux file system,
- webBootstrap.sh ~ Installs a basic webserver.
    - *Notes: Not all software is guaranteed to be complete.
   - ** (WIP**): indicates work is on going and package may not be stable or even usable.
#
### Running the Package
It is recommended to read the contents of the scripts to be assured of the installation process and what will be installed.  There may not be an associated uninstalling script, so uninstalling is the owners responsibility.
- There are two ways to install any of the packages listed under contents as file Format Type (??...??Bootstrap.sh).
  - 1. Upon installation of a new Linux installation as a bootstrap simply add the file to the Linux initialization bootstrap.
  - 2. If executing the script manually on a Linux after the O.S. has been installed, be sure to
       - execute as root ./??...??Bootstrap.sh
       - or as user with sudo access sudo ./??...??Bootstrap.sh
#
## Author Info

![About the Author](https://github.com/RMelanson/profile/blob/master/RobinPhoto.jpg)
- Name: Robin Melanson
- email: robin.e.melanson@gmail.com

[Back To The Top](#Package))
