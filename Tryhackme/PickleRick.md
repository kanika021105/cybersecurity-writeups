# TryHackMe - Pickle Rick Writeup

## Objective

Retrieve three secret ingredients hidden on the target machine.

## Skills Practiced

- Web Enumeration
- Linux Fundamentals
- Command Execution
- Privilege Escalation
- File System Navigation

## Methodology

### 1. Reconnaissance

- Inspected webpage source code.
- Discovered a username hidden in HTML comments.
- Checked robots.txt and discovered a password.

### 2. Authentication

- Logged into the Rick Portal using discovered credentials.

### 3. Enumeration

- Executed Linux commands:
  - whoami
  - pwd
  - ls
  - find

- Located hidden files and ingredients.

### 4. Privilege Escalation

- Investigated sudo permissions.
- Gained root privileges.

### 5. Final Objective

- Accessed protected files.
- Retrieved all three ingredients.

## Lessons Learned

- Always inspect source code.
- Check robots.txt during web enumeration.
- Misconfigured sudo permissions can lead to privilege escalation.
- Enumeration is often the most important phase of an assessment.