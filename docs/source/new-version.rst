==============
Versions 3.7
==============

Version 3.7.0
=============
Release Date: December 22, 2021

It's been almost 2 years since the last release. Although this isn't a major release in regards to functionality, this release is setting the foundation for larger changes in the future. 

**New**

* Project level viewing. 

    You can now view projects from a new Project Page. This not only provides context around the work in the Bug Tracker, but can also serve to limit the bugs to a specific project without needing to write a specific query or manage filters manually. 

* Added security scanning via Sonar Cloud. Now we know just how good our code is.

**Updated**

* Consistency on how pages open. They should all open in the same tab instead of in different tabs and pop-up windows.
* Documentation now resides on readthedocs.io (where you are probably reading this right now).
* Moved away from a website project and created a web application project.
* Created code behind files. This is the first step into a more mature architecture for the project.
* Updated to .NET Framework 4.7.2

**Fixed**

* Fixed a URL redirect exploit that could cause the user to be taken to a 3rd party site immediately after log in. Now the app knows that's not allowed and will only send you to internal pages following a log in.