## LINUX OS INSTALLATION WITH ZFS MIRROR

  __Question:__

    *What is Linux* Linux is an operating system just like windows and is one of the most popular platforms on the planet. One of the reasons being it has many free versions and it is open source.

    *What are some difference between windows OS installation and linux OS installation* The main difference in my opinion is windows protects the user from themselves. By this I mean it makes alot of the installation descions for you. There are no option for partioning, or specific hardware questions besides what drive you want to install windows on.

    *Explain some potential benefits of ZFS* ZFS offers pooled storage unlike most file systems. This enables you to create a file system that spans multiple drives. It also has copy-on-write which is a built in protection for file over writing and changing, where if the system crashes during a write the original data will not be lost. Lastly ZFS can handle implementing raid without any other software or harware.

    *Explain the benefit of a mirror* The first thing is that recovering data becomes alot easier. You dont have to take the database or system offline to do it and its alot safer. This also allows applications to continue to read from the database despite one or multiple failers. There is also no specific hardware or software required.

  __Deliverable:__
