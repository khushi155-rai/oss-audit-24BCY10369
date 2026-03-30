🚀 Open Source Audit — Git
👩‍🎓 Student Information
Name: Khushi Rai
Registration Number: 24BCY10369
Course: Open Source Software (VITyarthi)
Project Title: Open Source Audit

📌 Software Selected: Git

In this project, we explored Git, a distributed version control system created by Linus Torvalds in 2005. Git is widely used to monitor changes in source code and allows multiple developers to collaborate on a project smoothly without conflicts.

🎯 Project Objective

The main aim of this project is to study and understand an open-source tool, Git. Along with this, the project also focuses on:

Learning about its history, license, and working principles
Observing its usage in a Linux environment
Understanding the FOSS (Free and Open Source Software) ecosystem
Writing and executing shell scripts for automation and system-level tasks

🧠 Git Overview

Git follows a distributed approach, meaning every user has a complete copy of the repository on their system. This makes it fast, reliable, and efficient.

In Git:

Changes are stored as commits
Code is shared using push and pull commands
Different versions are combined using merge

🔄 Basic Workflow:

git init  
git add .  
git commit -m "message"  
git push  

⚙️ System Requirements

💻 Hardware:

Minimum 2GB RAM
Around 10GB free storage

🖥️ Software:

Linux OS (Ubuntu recommended)
Bash shell
Git installed

📦 Installation Steps

First, update system packages:

sudo apt update  
sudo apt upgrade -y  

Then install Git:

sudo apt install git -y  

Verify installation:

git --version  

📂 Project Structure

oss-audit-[rollnumber]/  
├── README.md  
├── script1.sh  
├── script2.sh  
├── script3.sh  
├── script4.sh  
└── script5.sh  

💻 Shell Script Details

🔹 Script 1: System Information
Displays system details such as kernel version, username, uptime, and OS information using commands like uname, whoami, and uptime.

Concepts used:

Variables
Command substitution
Output formatting

🔹 Script 2: Package Checker
Checks whether Git is installed and shows version and package details if available.

Concepts used:

if-else conditions
case statements
dpkg commands
grep and pipes

🔹 Script 3: Disk and Permissions
Analyzes directories to display permissions, ownership, and size.

Concepts used:

for loop
arrays
ls and du commands
awk

🔹 Script 4: Log Analyzer
Reads a log file, counts occurrences of a keyword (e.g., "error"), and shows recent matching entries.

Concepts used:

while loop
conditions
command-line arguments
counters

🔹 Script 5: Open Source Statement Generator
Takes user input and generates a short paragraph related to open-source concepts, then saves it into a file.

Concepts used:

user input (read)
string manipulation
file handling

▶️ How to Run the Project

Clone the repository:

git clone <your-repo-link>  
cd oss-audit-[rollnumber]  

Give execution permission:

chmod +x *.sh  

Run scripts:

./script1.sh  
./script2.sh  
./script3.sh  
./script4.sh /var/log/syslog error  
./script5.sh  

📊 Concepts Learned

Through this project, we learned:

Linux file permissions
Package management
Basics of shell scripting
Task automation using scripts
Log file analysis

🔐 Security Considerations

Scripts avoid unnecessary use of root privileges
Files are validated before access
No sensitive system data is modified

🌍 Importance of Git

Git plays a key role in modern software development by:

Managing different versions of code
Supporting teamwork and collaboration
Enabling open-source contributions
Keeping a complete history of changes

It is commonly used on platforms like GitHub and GitLab.

📌 Conclusion

This project provided both theoretical knowledge and practical experience with open-source tools. Git is an essential part of modern development, and this project helped in gaining hands-on experience with Linux and shell scripting.

📎 Future Scope

Add graphical interfaces for better usability
Enhance scripts with advanced automation
Integrate with CI/CD tools

🙌 Key Learnings

Working with Linux systems
Understanding open-source concepts
Writing and analyzing shell scripts
