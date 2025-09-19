# Set up Git if you haven't yet
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Create a new directory and initialize Git
mkdir my-first-repo
cd my-first-repo
git init

# Create a file and commit it
echo "# Hello GitHub" > README.md
git add README.md
git commit -m "Initial commit"

# Push to GitHub
git remote add origin https://github.com/your-username/my-first-repo.git
git branch -M main
git push -u origin main
