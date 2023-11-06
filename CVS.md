# CVS (Concurrent Versions System)
## Vendor
https://cvs.nongnu.org/
## Product Type
Open Source
## Description
CVS is a revision control system that improved upon the earlier RCS (revision control system) by operating as a client-server model (which allows multiple developers to work on a single file simultaneously) and adding support for repository-level change tracking (which allows project managers to better track progress).
## Learning Curve
Although CVS does have many GUIs (graphic user interfaces) that make it easier to use, experienced developers prefer using CLI (command line interface) for CVS, as it provides more flexibility, efficiency, and tool integration. If you are using a GUI, the learning curve varies based on the GUI you are using. If you are using a CLI, it may be difficult to learn as a beginner. However, if you have prior experience with using Git in a CLI, you may actually find CVS easier to use (since it uses a centralized and more intuitive system as opposed to git's distributed system).
## Cost
Since CVS is open sourced, it is **100% free**!
## Operating Systems
Although CVS was originally developed on a Unix-based system (and Unix still remains the most reliable and extensible operating system for CVS), it is currently a cross-platform system that also works on Windows,  iOs, and Linux.
## Advantages
* **Easy-to-Use**  
  CVS uses a centralized system that records the changes to the project in a single file. This provides a much simpler and more straightforward workflow than in a distributed system (with multiple file versions).
* **Binary Files**  
  CVS uses a delta compression system for managing the changes in a file, which works well for large files with few changes (such as binary files).
* **Reliability**  
  CVS has been around for over 30 years and has been reliably used for multiple projects (including many that are open-sourced).
## Disadvantages
* **Connectivity**  
   CVS runs on a single, centralized system. The only way to access a project in the system is by being connected to the network (such as the internet). That means that you cannot work on a project offline.
* **Slow Performance**  
  In CVS, you can only work with individual files (similar to RCS) and are required to make contact with the server for nearly every operation. This can be time-consuming and expensive.
* **Outdated Technology**  
  CVS is an older version control system that has largely been replaced by newer sytems (such as Git and Subversion). Although it is still used in some organizations, it isn't what you want to use if you need new and advanced features.
