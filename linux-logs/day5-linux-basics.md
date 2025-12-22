\# Day 5 – Linux Fundamentals (Structure \& Shell Basics)



\## Overview

This day focused on understanding the Linux system structure, common Linux distributions, and basic interaction with the system using the shell. These fundamentals are essential for working in security operations, incident response, and system analysis.



---



\## 1. Linux Structure



Linux follows a hierarchical filesystem structure where everything is organized under the root directory (`/`).



\### Important Directories

\- `/` – Root of the filesystem

\- `/home` – User home directories

\- `/etc` – Configuration files

\- `/var` – Logs and variable data

\- `/bin` – Essential user binaries

\- `/sbin` – System binaries

\- `/usr` – User utilities and applications

\- `/tmp` – Temporary files



Understanding the filesystem is critical for locating logs, configuration files, and binaries during investigations.



---



\## 2. Linux Distributions



A Linux distribution is an operating system built on the Linux kernel with additional tools and package managers.



\### Common Distributions

\- \*\*Ubuntu\*\* – User-friendly, widely used

\- \*\*Debian\*\* – Stable and secure

\- \*\*Kali Linux\*\* – Security testing and analysis

\- \*\*Red Hat / CentOS\*\* – Enterprise environments



Different distributions may use different package managers and configurations, but the core Linux concepts remain the same.



---



\## 3. Introduction to the Shell



The shell is a command-line interface that allows users to interact with the operating system.



\### Why the Shell is Important

\- Faster than GUI for administrative tasks

\- Essential for servers and remote systems

\- Widely used in security operations



Common shells:

\- bash

\- sh

\- zsh



---



\## 4. Shell Prompt Description



A typical Linux shell prompt looks like:



```bash

user@hostname:~$

Components



=> user – Current logged-in user



=> hostname – System name



=> ~ – Current directory (home)



=> $ – Regular user



=> # – Root user



Understanding the prompt helps identify privilege level and system context.







5\. Getting Help in Linux



Linux provides built-in help systems.



Common Help Commands

man <command>

<command> --help

help <command>





Examples:



man ls

ls --help





These tools are essential for learning new commands and understanding options.





6\. System Information



Linux provides multiple commands to gather system information.



Common System Information Commands

whoami

id

uname -a

hostname

pwd

ls





These commands help identify:



=>Current user



=>System architecture



=>Kernel version



=>Hostname



=>Current working directory



6 . Security Perspective



=> Linux servers are widely used in enterprise environments



=> Most security logs and services run on Linux



=> Understanding the shell and filesystem is critical for log analysis and incident response



=> Incorrect permissions or misconfigurations can lead to security breaches





\###Key Takeaways###



=> Linux uses a hierarchical filesystem structure



=> Distributions differ but core Linux concepts remain consistent



=> The shell is the primary interface for system interaction



=> Built-in help tools are powerful learning resources



=> System information commands are essential for security analysis





