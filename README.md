# Folder-path-lockdown

This source code written in PowerShell allows the user to lockdown, strip permissions, and add newly created active directory groups to a specified folder path in their network's shared drive.

**What it does:** Locking down a folder path on our network’s shared drive

**Purpose:** The purpose of this script was to consolidate and mitigate all the manual steps it takes to lock down a specific folder path located on our network’s shared drive. The process is tedious as where you will manually need to create two new active directory security groups for read\write and read-only access, remove all inherited groups that belong to the folder path, add members and owners of the groups, and provide the correct permissions. 

