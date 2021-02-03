## STORAGE AND RAID

  __Section 1:__  RAID

    `What does RAID offer systems in terms of making a system more fault tolerant? `
      Enabling a raid allows multiple drives to have redundancy. So, for example RAID 1 requires two drives or more to replicate information on two drives in the same way, this allows for one drive to fail and no information loss. This is referred too as mirroring because the same information is on the drives. Then RAID 10 is similar but 2 drives are treated as 1. So 2 drives out of 4 have the same information on them and the other 2 have a different set of information.

    `In terms of RAID, are there levels / configurations that do NOT provide any “protection” for data or hardware?`
      Yes raid, 0 offers no mirroring or protection but increase performance.

    `Is RAID a replacement for backup?`
      No, it is not.

    `Why? or Why not?`
      Because raids rely heavily on all drives working together. If there is multiple drive losses then most raids will lose data.

    `How is the newer generation of RAID utilized within large organizations with considerable data storage and performance needs?  Said differently, what is an example of how modern RAID is implemented for either large organizations or organizations that need to storage and retrieve a large amount of data reliably.`
      Modern raid arrays try and get the best of both worlds. This means that not only is there fast performance but also redundancies to help protect data. To go along with this new drive technology that is built for raid arrays has helped to stop faults from happening and data protection.

    `What in terms of the language (ways of referring to RAID deployment types) can be confusing and at times technically incorrect?`
      Confusion is common among the standard names and symbols for prefixes for binary multiples for use in the fields of data processing and transferring.

    `Hint: Think in terms of the unfortunately used terms of “Hardware” and “Software” RAID.`

  __Section 2:__  Performance and Capacity

    `When thinking about disks, what is one aspect of performance that we want to optimize?`
      Disks first require more time to retrieve data then other storage devices like solid state. Since hard disks need to spin up and move in order to get any data it takes more time after your computer is started up to get data.

    `(Note:  We are trying to Limit this).`

    *Deliverable:*
      `In order to practice raid configuration all I did was grab a spare hard drive and mirrored it to my 2nd SSD on my main computer. Of course, I used the VM partition of that 2nd SSD. This was accomplished through disk management.  `
