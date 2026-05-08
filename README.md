# Github User Backup Tool

Stupid simple GitHub backup tool. It will back up all repositories for a single user without user credentials. Usefull for backing up either suspicious repositories, making backups of your own public repos, and archiveal purposes.

## Requirements
git curl jq

## Usage
```bash
chmod +x ./github-backup.sh
github-backup.sh <github_username> [backup_dir]
```
