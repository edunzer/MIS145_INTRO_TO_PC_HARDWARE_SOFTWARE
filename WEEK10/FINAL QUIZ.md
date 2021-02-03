## FINAL QUIZ

  __Individual:__

    *Mention some of the most interesting technologies that you have learned more about over the course of the term. Said differently: What technologies are you most interested in studying further?*
    -Although I knew alot about the subjects that were in this class I did learn more about raid and file systems. This is something that I never got into because I had never had a use for it thus far. Now that I do know more I might implement it on my home security computer that records all the video from my cameras.

  __Questions:__

    *(Q1.) What two microprocessor companies have been dominant in the computing market for the longest time?*
    -Intel and Samsung are the two that come to mind.

    *(Q2.) What is a new(er) microprocessor that is gaining greater adoption (think mobile and large scale datacenter implementations)?*
    -AMD is starting to gain traction in datacenters after 2 years of targeted business development but they dont have any small form factor chips for phones. Exynos is currently a rising star in mobile phone chips but they dont have any server chips.

    *(Q3.) With regard to processors, what are some of the main features that differentiate processors. Said differently, how do IT professionals make decisions between one processor and another?*
    -Number of cores, number of threads, what is the application that the chip will be used for. Many chips differ in how they preform to different tasks. Many gaming chips have a high core count and clock speed but cant compare to some server chips that have lower clock speeds when it comes to crunching data.

    *(Q4.) When thinking about user interfaces to operating systems (Windows, Linux, etc.), what primary advantages or disadvantages can you identify that help administer / manage systems with consistent / reproducible results?*
    -Well the main difference between windows, Linux, and mac is the ability of the user. Linux is an opensource OS that is used widely by people with servers because its a light and clean OS that doesn't add alot to the system. Mac is definitely clean but it extremely simple and in many ways takes care of common choices for the user. Windows is what I think of as the in-between the two extremes. So obviously the disadvantages of Mac and Windows is that its a closed system in some respects and has less customization. But both do make it easier for the user to use basic computer functions.

    *(Q5.) What problem does virtual memory solve?*
    -It solves having a shortage of physical memory by taking some of that memory and putting it in disk storage.

    *(Q6.) What problem do you feel virtual memory does not solve?*
    -I think the overall fact of not having enough memory is still there. Disk storage is often a lot slower then physical memory making virtual memory a Band-Aid fix to the problem of not having enough memory.

    *(Q7.) What commands could you use under Windows and Linux to display the network information for your system’s interfaces (provide examples)?*
    -ifconfig or ipconfig: will tell you about your network interfaces, the state that they're in, your assigned IP address, and even provide some counts of packets that have crossed the interface
    -ping: It might tell you that you can reach a remote system, but you can't assume a system is down if you don't get a response
    -traceroute: will attempt to provide a list of all the routers your connections cross when reaching out to a remote system
    -netstat: can tell you about ongoing connections on the local system and ports that are listening, indicating that services are waiting for requests to come through.


    *(Q8.) What is key idea in storage that we use to offer fault tolerance (i.e. to enable our systems to cope with disk failure, etc.)?*
    -redundancy is the biggest defender against disk failure. This enables data to be stored in multiple locations.

    *(Q9.) What considerations that we make when selecting storage (spinning disks, SSDs, PCIe Flash, etc.)?*
    -size, speed and price are probably the biggest questions when picking storage. Size is also a common factor but often speed and small formfactor are related.

    *(Q10.) Is RAID a replacement for Backup? (Why or why not, etc.).*
    -No raid is not a backup, a backup is completely separate from the system its backing up. Raid is just a way to improve upon reliability.

    *(Q11.) Similarly: Is Backup a replacement for RAID (and related technologies)?*
    -No because raid is connected to the system/drives and also often times provides benefits like speed, and reliability.

    *(Q12.) What are some controls that operating systems offer to aid in providing appropriate access to / or use to control access to resources (directories, files, etc.)?*
    -There are typical passwords and locks that you can put on files and systems. Windows offers some user restrictions, and im sure that there is ways to do this on linux but none that im awear of that are built in. Linux does offer alot of file protection options thats for sure.

    *(Q13.) What is access control with regard to filesystems?  Does this relate to user accounts? Along these lines, how do the concept of privilege and permission relate.*
    -Access control is what allows certain users to access certain files and applications on the system. This often enables a different class system among users, where the admin is allowed to see and control everything and most of the other sues are restricted to only certain information. The biggest part of admin access is that they are the only ones that can control system settings that can changes settings throughout the system.

    *(Q14.) What is a firewall?  Explain the protection that a firewall can provide.  Also indicate any relevant features that you wish to highlight.*
    -A firewall is another layer of security that monitors incoming and outgoing network traffic and block data packets. This protects your home local network against the network that you are connected too. There are many different kinds of firewalls that have different levels of involvement and invasiveness into the systems and networks.

    *(Q15.) After completing the Assignment relating to Cloud Computing vs. On Premise computing, what did you notice about your own usage of Public Cloud Computing (i.e. either do you run servers on AWS EC2, Joyent, Azure, etc. or do you use services that are offered from those Public Clouds (Google Drive, Dropbox, etc.). Indicate either services that you use or observations that you have made about their usage within your own company / organization / life.*
    -I dont personally use any services like AWS that host servers but I guarantee that I use websites and other services that do use those. The only public clouds that I am currently using is GitHub because they recently allowed for free private repositories. Besides that I dont use google drive, and especially not drobox because its so bad in comparison to GitHub. There are a couple gaming services that have cloud storage information but im not aware of what kind. 
