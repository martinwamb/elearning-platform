Here's the complete, runnable code for completing the initial commit in the "Elearning Platform" project:

# Step 1: Create repository on GitHub
gh repo create martinwamb/elearning-platform --public

# Step 2: Initialize a new Git repository and add remote origin
git init .
git remote add origin https://github.com/martinwamb/elearning-platform.git

# Step 3: Add the necessary files to version control
echo "# Elearning Platform" > README.md
mkdir -p src
echo "" > src/index.js
echo "const App = () => { return <h1>Welcome to the Elearning Platform</h1>; };" >> src/index.js

# Step 4: Write a commit message
git add .
git commit -m "Initial commit with basic structure and README"

#