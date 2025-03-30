# Backup Script

## Overview
This Bash script backs up files modified in the last 24 hours from a target directory to a destination directory.

## How It Works
1. Checks for valid arguments and directories.
2. Identifies files modified in the last 24 hours.
3. Creates a compressed archive (`backup-<timestamp>.tar.gz`).
4. Moves the archive to the destination directory.

## Notes
- Ensure script has execution permission (`chmod +x backup.sh`).
- Run with `sudo` if permission issues arise.

## Author
Automates file backups using Bash.
