# git

## Concept 1: What Is Version Control? Setting Up Git

```bash
# Without Git: Only one version exists
my-project/
  index.html  # This is the only version

# With Git: All versions are tracked
my-project/   # repository
  index.html  # Current version
  .git/       # Hidden folder with ALL previous versions
```

#### Installing Git

```bash
# Check if Git is installed
git --version

# If not installed:
Windows: Download from git-scm.com

```

#### Basic Git Configuration

```bash
# Set your name (appears in commit history)
git config --global user.name "Your Name"

# Set your email (must match GitHub email)
git config --global user.email "your.email@example.com"

# Check your configuration
git config --list
```
