# DevOps Basics by Ravi K Malhotra

##    Tools to install locally on your laptop/desktops
- Oracle VM Virtual Box or VMWare Workstation
- Git Bash
- Vagrant
- Chocolatey for windows
  - It's a tool in windows to install software and packages through command line instead of traditional google search, plus download and then install.
  - access the URL -- https://chocolatey.org/install
  - open power shell on your local system as in administrator
  - First, run this commaand in the power shell [ Get-ExecutionPolicy ], and check the result
  - if it returns Restricted, then run [ Set-ExecutionPolicy AllSigned ] or [ Set-ExecutionPolicy Bypass -Scope Process ].
  - After that run the main command to install the chocolatey on windows wiht the following command
  - Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
  - wait for few seconds
  - If you don't see any errors, you are ready to use Chocolatey! Type choco or choco -? now 
- Homebrew for Mac
  - similiar to Choco, you have Brew for Mac systems.
- JDK8
- Maven
- Intellij
- Sublime Text Editor
- AWS CLI
- Azure CLI
- GCP CLI
- Terraform
##    Signup with different apps and platforms
- GitHub
- Domain purchase
- Dockerhub
- Sonarcloud
##    AWS, Azure or GCP specific pre-requisites.
- create a free tier account with AWS
- IAM with MFA
- Billing Alarm
- Certificate Setup
- 

- 
