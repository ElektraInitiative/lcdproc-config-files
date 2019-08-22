# config-files

You can help us build a reliable merge tool by submitting your configuration files to this repository or by sending an email to e1634025@student.tuwien.ac.at

[Elektra](https://www.libelektra.org) serves as a universal and secure framework to access configuration parameters in a global, hierarchical key database. 

Its new three-way merge should be able to merge three versions of a configuration file that occur during a package upgrade:
The default version from before the upgrade, the one with all modifications (such as changed values or additional comments) and the new default from the upgraded package.
This way the required amount of manual interaction is reduced for desktop distributions or completely avoided for embedded systems.

To develop the new tool we rely on test cases.
Apart from many synthetic tests we use real-world data for our tests.
Real-world data helps us identifying which features are important and that those important parts work properly.
We are looking especially at /etc. Thus, contributing is as easy as archiving this folder and uploading it.

Please add configuration files from Debian 9 (Stretch) into the `debian-stretch` directory and configuration files from other sources into the `other` directory.
Please add meta information such as your operating system as well, especially when contributing into `other`. 
You will have to do a pull request.
