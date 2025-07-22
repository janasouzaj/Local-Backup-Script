# Local Backup Script Using Bash

A simple and configurable bash script to automate your **local backups** of directories on linux. It compresses selected folders, saves them in a specified directory, and removes old backups automatically based on your retention policy.


## Features

- Backup of multiple directories
- Compression using `tar.gz`
- Automatic deletion of old backups
- Logging of all backup activities
- Configurable via `.conf` file


## Project Structure

backup-script/
├── backup.sh # Main script
├── backup.conf # Configuration file
├── logs/
│ └── backup.log # Log file
└── README.md # This file
