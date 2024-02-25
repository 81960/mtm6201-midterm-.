# Initialize a new Git repository
git init

# Add README file
echo "# MTM6201 Midterm Project" >> README.md

# Commit changes
git add .
git commit -m "Initial commit"

# Create a new repository on GitHub and push code
git remote add origin <repository_url>
git branch -M main
git push -u origin main
