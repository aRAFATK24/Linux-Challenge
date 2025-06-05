# Linux System Administration Challenge

This repository contains solutions for a comprehensive Linux system administration challenge covering basic to advanced tasks. The challenges test skills in file management, user administration, process control, networking, and shell scripting.

## Challenge Tasks

### Task 1: Basic Linux Commands
- Create directory structure (/home/devops/academy/project)
- File creation and management (README.md, notes.txt)
- Permission management (chmod 600, 644)

### Task 2: User and Group Management
- User creation (student1) and password setting
- Group creation (devops) and user assignment
- Directory permissions for groups
- Disk usage monitoring

### Task 3: Process Management
- Process listing and logging
- Background process creation (timestamp logging)
- Process termination
- System resource monitoring

### Task 4: Networking
- Network configuration display
- Connectivity testing (ping)
- Port status checking
- Firewall configuration (UFW)

### Task 5: Shell Scripting
- Backup script with error handling
- Automated cleanup script with cron scheduling
- Log rotation script

## Advanced Challenges
- *Resource Monitoring Script*: Tracks CPU, memory, and disk usage with alerting
- *Bulk User Creation*: Automated user provisioning from a list file

## Usage

Each task has corresponding commands and scripts in the repository. Key scripts include:

bash
# Backup script
./backup.sh

# Cleanup script (run daily via cron)
./cleanup.sh

# Resource monitoring
./resource_monitor.sh

# Bulk user creation
./bulk_user_add.sh user_list.txt


## Requirements

- Linux system (tested on Ubuntu)
- sudo privileges for administrative tasks
- Basic utilities: tar, cron, ufw, etc.
