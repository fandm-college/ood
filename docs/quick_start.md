---
title: OOD for SSH users
layout: page
nav_order: 2
---

{: .note }
>  This guide is meant as a quick introduction to OpenOnDemand (OOD) 
>  for users who in the past, had generally accessed the cluster
>  using SSH and the command line.  
>
>  Please see the other sections of the OOD documentation (on the left)
>  for more in depth information on the capabilities of OOD
>

# Accessing OOD

The OOD web portal can be accessed via this [link](https://rcs-scsn.fandm.edu)

Use your F&M netID and password (the same ones you use to access your F&M Google mail)
to login.

{: .note }
>  Access from off-campus requires F&M's Global Protect VPN
>

# Accessing a terminal

If you normally access the cluster using SSH, the easiest/fastest way to interact with the cluster
is to use OOD's terminal.  Terminal can be accessed by selecting

- **Clusters**
- **F&M Research Cluster Shell Access**

![OOD terminal menu item](../assets/images/terminal.png)

{: .warning }
>  You should not use the terminal for any long running commands (e.g., scp/rsync, monitoring log files, etc.)
>  because of the potential for timeouts due to inactivity
>

# Transferring files

For complete details on transferring files to/from the cluster please refer to 
[file upload/download documentation](file_management.html).  In brief,

- Use OOD's file manager (**Files-->Home Directory**) to upload/download files up to 10GB in size

![OOD file manager menu item](../assets/images/file_manager.png)

- If you routinely work with larger files, then in all likelihood we have large network storage
  on the cluster for your research.  You should move files to that however you normally might
  do that (e.g., via Globus).  You can then either use the terminal(and Linux commands) or the File Manager to 
  copy files between the network storage and your home directory on the cluster.




