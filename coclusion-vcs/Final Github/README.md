
# GitHub Version Control System (VCS) Setup: Proof of Concept

| Author      | Created on | Version   | Last updated by | Last edited on | Reviewed By L0 | Reviewed By L1 | Reviewed By L2 |
|-------------|------------|-----------|-----------------|----------------|----------------|----------------|----------------|
| Chander Kant       | 13-10-24   | Version 1 | Chander Kant   | 15-10-24       |                |                |                |

## Table of Contents
1. [Purpose](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#purpose---)
2. [Pre-requisites](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#pre-requisites---)
   - [System Requirements](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#system-requirements---)
   - [Dependencies](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#dependencies---)
3. [Architecture](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#architecture--)
4. [Step-by-step installation of GitHub](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#step-by-step-installation-of-github--)
5. [Conclusion](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#conclusion--)
6. [Contact Information](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#contact-information--)
7. [Reference](https://github.com/MyGurukulam-p11/Documentation-P11/blob/Chanderkant_Scrum_24/VCS%20Design%20+%20POC/Feature%20of%20VCS/POC%20to%20setup%20recommended%20VCS/README.md#references---)


## Purpose  :-
This Poc demonstrates how to set up and use GitHub as a Version Control System. GitHub provides a centralized platform for collaborative software development, offering features like version control, issue tracking, and project management.

## Pre-requisites  :-

## System Requirements  :-

| Hardware Specifications | Minimum Recommendation |
|-------------------------|------------------------|
| RAM                     | 1 GB                   |
| Disk                    | 8 GB free space        |
| OS                      | Windows 10, macOS 10.14, Ubuntu 18.04 or later |

## Dependencies  :-

| Name    | Version | Description |
|---------|---------|-------------|
| Git     | 2.34    | Distributed version control system |


## Architecture :-
![Architecture VCS](https://github.com/user-attachments/assets/c63761a8-b791-4e64-99a6-d687c2d6a624)

## Step-by-step installation of GitHub :-

1. Install Git:
   ```bash
   # Windows (using Chocolatey)
   choco install git

   # macOS (using Homebrew)
   brew install git

   # Ubuntu
   sudo apt-get update
   sudo apt-get install git
   ```

2. Create a GitHub account at [github.com](https://github.com)

3. Create a new repository on GitHub:
   - Click the "+" icon in the top-right corner
   - Select "New repository"
   - Name your repository
   - Click "Create repository

![image](https://github.com/user-attachments/assets/85372eff-8f07-4247-a638-c0bf0142e312)
![image](https://github.com/user-attachments/assets/e1cdfa46-c663-40bf-9ade-54a85cb552f5)



4. Set up local repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   # Make changes to files
   touch index.html
   git add index.html
   git commit -m "added index.html"
   git push origin main
   ```
![image](https://github.com/user-attachments/assets/b71a525f-1fab-4728-8482-cdb8d888aa17)
![image](https://github.com/user-attachments/assets/dcd79a3b-03cf-4920-ad9a-0793d7cb9d96)



## Conclusion :-

In this Proof of Concept (PoC), we demonstrated the basic process of creating a repository, cloning it, and pushing changes. This workflow allows developers to track modifications, collaborate smoothly, and ensure an organized approach to managing project files and updates. By following these steps, teams can streamline their development efforts and enhance productivity across the board.

## Contact Information :-

| Name | Email address|
|------|---------------------|
| Chander Kant   | chanderkant.soni.snaatak@mygurukulam.co |

## References  :-
| Links                                             | Descriptions                                                    |
|---------------------------------------------------|-----------------------------------------------------------------|
|https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks |Git Documentation - Customizing Git|
