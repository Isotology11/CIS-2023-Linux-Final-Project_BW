# CIS-2023-Linux-Final-Project_BW

#!/bin/bash

# Variables 
GITHUB_REPO_URL="(https://github.com/Isotology11/CIS-2023-Linux-Final-Project_BW)"
REPO_NAME="CIS-2023-Linux-Final-Project_BW"

# Clone the repository
git clone $GITHUB_REPO_URL
cd $REPO_NAME

# Create README.md file
echo "# CIS2023 Linux Final Project BW" > README.md
echo "This project contains a bash script that counts from 1 to 50 and outputs the result in the terminal." >> README.md

# Stage and commit README.md
git add README.md
git commit -m "Initial commit: Added README.md"
git push origin main

echo "Repository setup complete!"
