# How to Upload Files and Folders to a GitHub Repository

1. Navigate to the Directory or Folder You Want to Upload
cd path/to/your/directory

# Initialize Git Repository
git init

# Add Files and Folders
git add .

# Check Status
git status

# Commit Changes
git commit -m "Your commit message"

# Set Remote Repository URL
git remote add origin git@github.com:user_name/repository_name

# Pull Remote Changes (if you want to upload all the folder to the main branch)
git pull origin main --allow-unrelated-histories

# Push Changes to GitHub
git push origin master:main
