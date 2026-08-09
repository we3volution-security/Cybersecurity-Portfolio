# Linux Fundamentals

**Platform:** TryHackMe
**Path:** Cyber Security 101
**Module:** Linux Fundamentals — Parts 1, 2 & 3
**Status:** ✅ Completed
**Environment:** Linux virtual machines / terminal / remote SSH
**Lab Type:** Hands-on VM and command-line labs

---

## Overview

The Linux Fundamentals module developed practical confidence working with Linux systems through the command line.

Across three connected rooms, the learning progressed from basic interaction with an interactive Linux machine, through remote access and permissions, into system processes, automation, package management and logging.

The practical work involved using Linux machines directly rather than simply learning commands theoretically.

TryHackMe's progression moves from an interactive Linux machine in Part 1, to remote Linux access using SSH in Part 2, and then into processes, automation, package management and logs in Part 3.

---

# Practical Environment

The module provided hands-on Linux environments that I interacted with directly.

The progression included:

```text
Linux VM
   ↓
Command-line interaction
   ↓
Filesystem investigation
   ↓
Remote Linux access
   ↓
SSH
   ↓
Permissions & users
   ↓
Processes & services
   ↓
Automation & packages
   ↓
System/application logs
```

Part 1 provided an interactive Linux machine directly in the browser.

Part 2 introduced connecting to and controlling a remote Linux machine using SSH.

Part 3 continued with a deployed Linux machine and practical system-administration concepts.

---

# What I Learned

## Linux Command Line

Developed practical familiarity with using the terminal as the primary interface for interacting with a Linux system.

I worked with commands for:

* Navigating the filesystem
* Listing and investigating files
* Reading file contents
* Finding files
* Searching file contents
* Counting lines/data
* Creating and manipulating files and directories
* Identifying file types
* Working with users and elevated privileges
* Investigating processes
* Managing services
* Working with system locations and configuration

The emphasis was on **using the commands to investigate and interact with a live environment**, rather than memorising commands in isolation.

---

# Practical Commands & Techniques

The following are examples of commands and techniques I actually worked with during the module.

### Filesystem navigation and investigation

I used commands including `ls`, `ls -a`, `cd`, `pwd`, `cat` and `find` to navigate the filesystem, identify files and directories, establish my current location and investigate file contents.

I also worked with options and combinations such as `-1`, `-a1` and filename searches including:

```bash
find -name "*.txt"
```

This developed practical familiarity with locating information within a Linux filesystem.

### Searching and analysing information

I used `grep`, recursive searching with `grep -r`, and `wc` to search file contents and investigate information within files.

This was particularly useful for understanding how command-line tools can be combined to investigate larger amounts of information rather than manually reading every file.

### Creating and manipulating data

I worked with:

```text
touch
mkdir
mv
rm
>
>>
```

This included creating files and directories, moving and removing files, and redirecting command output into files.

### Shell operators

I practised using shell operators including:

```text
&
&&
>
>>
```

This introduced running commands in the background, chaining commands conditionally, redirecting output and appending output.

### File and system investigation

I used `file` to identify file types and investigated important Linux filesystem locations including `/var`.

### Users and privileges

I worked with:

```text
su
sudo
sudoers
sudo find
```

This introduced switching users, elevated privileges and the importance of understanding which users and commands have administrative permissions.

### Remote access

Part 2 introduced SSH as a method of accessing and controlling a remote Linux machine.

This was an important progression from simply working locally to interacting with a remote system.

### Utilities and system activity

Later practical work included:

```text
wget
python3
python3 -m
ps
ps aux
systemctl
cron
```

These introduced downloading resources, running Python, investigating processes, managing services and understanding scheduled tasks/automation.

---

# Practical Skills Demonstrated

Through the three rooms I gained hands-on experience with:

* Linux command-line interaction
* Filesystem navigation
* File and directory investigation
* Searching for files
* Searching file contents
* Output redirection
* Shell operators
* File manipulation
* User switching
* Privilege escalation concepts
* Linux permissions
* Remote access using SSH
* Process investigation
* Service management
* Scheduled tasks/automation
* Package/system utilities
* Basic scripting and Python execution
* System and application logs

---

# VM / Hands-On Experience

A key part of this module was working directly with Linux virtual machines.

This included:

* Deploying a Linux lab environment
* Working inside the VM through a terminal
* Executing commands against the live system
* Investigating the filesystem
* Connecting to a remote Linux machine
* Working with users and permissions
* Investigating processes and services
* Working with system configuration and logs

This provided practical experience that goes beyond simply completing theory-based questions.

---

# Cybersecurity Relevance

Linux command-line ability is a core cybersecurity skill.

The skills developed here are directly relevant to:

### Penetration Testing

Command-line proficiency supports activities such as:

* Enumeration
* File discovery
* Information gathering
* Remote access
* Permission analysis
* Process investigation
* Service enumeration
* Script execution

### Defensive Security

The same knowledge can be used to:

* Investigate suspicious processes
* Examine logs
* Identify running services
* Investigate system changes
* Understand user privileges
* Analyse system activity

### IT / Systems Administration

The module also developed transferable skills relevant to:

* Linux administration
* Server support
* Remote troubleshooting
* System investigation
* Basic automation

---

# Security Mindset Developed

Rather than simply executing commands, the practical exercises began developing a more investigative approach to systems.

This provides an important foundation for later enumeration and penetration-testing work.

---

# Evidence

Evidence will be added as screenshots are organised.

**Evidence location:**

`/evidence/screenshots/security-101/linux-fundamentals/`

### Planned evidence

* Linux lab environment
* Terminal interaction
* Filesystem navigation
* File discovery
* `grep` / recursive search
* Shell operators
* File manipulation
* User/privilege investigation
* SSH remote connection
* Process investigation
* Service management
* Automation / scheduled tasks
* Relevant system investigation

Screenshots will demonstrate practical interaction without publishing flags, credentials or complete room solutions.

---

# Key Takeaway

The Linux Fundamentals module moved my Linux knowledge from basic awareness to practical command-line interaction.

I can now approach a Linux environment with greater confidence, navigate and investigate the filesystem, interact with users and permissions, connect to remote systems, examine processes and services, and use command-line tools to gather and manipulate information.

This forms an important technical foundation for my continued cybersecurity training, particularly my longer-term interest in penetration testing and offensive security.

---

## Further Development

Future Linux security development will build towards:

* Enumeration
* Service discovery
* Privilege escalation
* Persistence
* Shells
* Security tooling
* Log analysis
* Vulnerability assessment
* Linux-based penetration testing
