# Create a new README file
echo CATWIFSHOES" >> README.md

# Initialize Git
git init

# Add README file to staging
git add README.md

# Commit the changes
git commit -m "first commit"

# Set the main branch
git branch -M main

# Connect to your GitHub repository
git remote add origin https://github.com/sadekwhop/-CATWIFSHOES.git

# Push your files to GitHub
git push -u origin main
