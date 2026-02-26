Table of Contents:

Section 1: System Inventory

Section 2:The Access Control Model

Section 3: Top Process Analysis and Risk

Section 4: Git Submission



# Lab 02: System Audit 
 
**Student Name:** [Arielle Sidberry]   
**Date:** [2/3/2026] 
 
--- 
 
## Section 1: System Inventory 
 
| Component | Specification | 
|-----------|---------------| 
| Operating System | [Windows 11 Pro Version 25H2]  

Total Installed RAM | [ 16.0 GB (15.5 GB usable] 
| CPU Model & Clock Speed | [Intel(R)Core(TM) Ultra 5 135U @ 2.54 GHz] 
 
--- 
 
## Section 2: The Access Control Model 
 
### Model Definition 
My operating system ([Windows 11 Pro]) uses [RBAC] as its primary Access Control Model. 
 
**Definition:** [Role-Based Access Control is an access control model where permissions are assigned to roles, and users receive access based on their assigned job role within an organization (Microsoft, n.d.).] 

Citation: Microsoft. “What Is Access Control?” Microsoft Security 101, Microsoft, https://www.microsoft.com/en-us/security/business/security-101/what-is-access-control#:~:text=Role%2Dbased%20access%20control%20(RBAC,their%20jobs%E2%80%94and%20no%20more
. Accessed 03 Feb. 2026.
 
### Relationship to Permissions 
[ In RBAC, users are assigned read, write, and execute permissions based on their assigned role.] 
 
### Principle of Least Privilege (PoLP) Application 
[ Administrators enforce the Principle of Least Privilege by using Role Based Access Control to assign permissions to the roles based on job functions. The users are added to the role based on their job responsibilities.] 
 
**Concrete Example:** 

- Windows: The Administrator sets up security groups that define users’ read, write, and execute permissions. Windows enforces these permissions by preventing unauthorized access, requiring approval from the designated user or manager. For example, on my work computer, I only have access to applications and information necessary for my job duties. If I need additional access to certain files to make edits or write data, I must obtain approval from the manager responsible for those files.
--- 
 
## Section 3: Top Process Analysis & Risk 
 
### Process 1: [Bash] 
- **Process Name:** [bash.exe] 
- **Process ID (PID):** [1492] 
- **Resource Consumption:** [CPU: 0%]
- What is Bash? An application used to interact with an operating system. It allows users to run commands, manage files and directories, automate tasks with scripts, and execute programs.
 
**Security Risk Hypothesis:** 
[Example: An attacker could execute unauthorized commands and gain access to sensitve files or network resources.] 
 
### Process 2: [Google Chrome] 
- **Process Name:** [chrome.exe] 
- **Process ID (PID):** [28036] 
- **Resource Consumption:** [RAM: 3.27 GB]
- What is Google Chrome? Google Chrome is a web browser developed by Google that allows users to access and navigate the internet.
 
**Security Risk Hypothesis:** 
[Example: The attacker could take advantage of a browsers vulnerability to compromise the system, users data and network access and leak information.] 
 
### Process 3: [Adobe Acrobat] 
- **Process Name:** [armsvc.exe] 
- **Process ID (PID):** [5680] 
- **Resource Consumption:** [RAM: 170 KB]
- What is Adobe Acrobat? Adobe Acrobat is a program that lets you view, create, edit, and share PDF files.
 
**Security Risk Hypothesis:** 
[Example: The attacker can use a malicious PDF file to compromise the system and steal data.] 

## Screenshots of Operations System/ Git Clone

 <img width="1851" height="850" alt="System Inventory 1" src="https://github.com/user-attachments/assets/ef619d33-0e5c-474b-a8bf-5963c658567b" />


<img width="1852" height="622" alt="System Inventory 2" src="https://github.com/user-attachments/assets/34a042a5-d564-4a79-ae1c-bccedab0e087" />


<img width="713" height="251" alt="image" src="https://github.com/user-attachments/assets/865b39d0-728d-45a0-9e71-c763617fc59c" />

--- 
 
## Section 4: Submission Checklist 
 
- [ ] File named correctly: System-Audit.md 
- [ ] All sections completed with accurate information 
- [ ] Proper Markdown formatting used 
- [ ] Spell-checked and proofread 
- [ ] Committed to GitHub with meaningful message (e.g., "Lab 02: Initial System Audit") 
- [ ] Repository link verified 

https://github.com/asidberry/System-Audit.md.git 
