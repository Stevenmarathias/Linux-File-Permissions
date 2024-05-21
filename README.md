# Linux-File-Permissions

mkdir src

touch src/manage_permissions.sh

touch README.md

touch .gitignore

#!/bin/bash

# Check file and directory details
ls -la /home/researcher2/projects

# Change file permissions
chmod g-x /home/researcher2/projects/drafts
chmod 600 /home/researcher2/projects/.project_x.txt
chmod 644 /home/researcher2/projects/project_m.txt
chmod 664 /home/researcher2/projects/project_k.txt
chmod 644 /home/researcher2/projects/project_r.txt
chmod 644 /home/researcher2/projects/project_t.txt

# File Permissions in Linux

## Project Description
This project involves updating file permissions for certain files and directories within the projects directory to ensure they reflect the appropriate level of authorization and help keep the system secure.

## How to Use
1. Place the `manage_permissions.sh` script in the desired directory.
2. Run the script with appropriate permissions to update the file and directory permissions.
   ```bash
   bash src/manage_permissions.sh

ls -la /home/researcher2/projects
chmod g-x /home/researcher2/projects/drafts
chmod 600 /home/researcher2/projects/.project_x.txt
chmod 644 /home/researcher2/projects/project_m.txt
chmod 664 /home/researcher2/projects/project_k.txt
chmod 644 /home/researcher2/projects/project_r.txt
chmod 644 /home/researcher2/projects/project_t.txt

git add .
git commit -m "Initial commit with script and README"
git push origin main
