# Task 4: Git Version Control & Express.js Application

## Git Commands Reference


**SCREENSHOTS**
   ![SS](images/Screenshot%20from%202025-04-11%2012-15-55.png)
   ![SS](images/Screenshot%20from%202025-04-11%2012-16-22.png)
   ![SS](images/Screenshot%20from%202025-04-11%2012-21-09.png)
   ![SS](images/Screenshot%20from%202025-04-11%2012-26-40.png)
   ![SS](images/Screenshot%20from%202025-04-11%2012-27-37.png)
   ![SS](images/Screenshot%20from%202025-04-11%2012-28-23.png)

### 1. Repository Management
```bash
# Initialize repository
git init

# Add remote repository
git remote add origin <repository-url>

# Clone repository
git clone <repository-url>
```

### 2. Basic Git Operations
```bash
# Check repository status
git status

# Stage changes
git add <file-name>
git add .                  # Stage all changes

# Commit changes
git commit -m "descriptive message"

# Push changes
git push origin <branch-name>
```

### 3. Branching Operations
```bash
# Create new branch
git branch <branch-name>

# Switch branch
git checkout <branch-name>

# Create and switch branch
git checkout -b <branch-name>

# List branches
git branch
git branch -a             # List all branches including remote
```

### 4. Tag Management
```bash
# Create tag
git tag v1.0.0

# Create annotated tag
git tag -a v1.0.0 -m "Version 1.0.0"

# Push tags
git push origin --tags

# Delete tag
git tag -d v1.0.0
```

## Project Implementation Steps

1. **Initialize Project**
   - Created basic Express.js application structure
   - Set up Git repository
   - Added `.gitignore` file

2. **Express Application Setup**
   - Installed dependencies
   - Created basic server configuration
   - Implemented routes

3. **Version Control**
   - Made initial commit
   - Created development branches
   - Tagged release versions

## Best Practices

1. **Commit Messages**
   - Use clear, descriptive messages
   - Follow conventional commit format
   - Reference issue numbers when applicable

2. **Branching Strategy**
   - Main branch for stable code
   - Feature branches for development
   - Delete merged branches

3. **Tagging**
   - Use semantic versioning
   - Tag major releases
   - Include detailed release notes

## Project Structure
```
.
├── src/
│   └── index.js
├── package.json
├── .gitignore
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Switch to project directory:
   ```bash
   cd <project-directory>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start development:
   ```bash
   npm start
   ```

## Contributing

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```

2. Make changes and commit:
   ```bash
   git add .
   git commit -m "feat: add new feature"
   ```

3. Push changes:
   ```bash
   git push origin feature/your-feature
   ```

4. Create Pull Request on GitHub

## License

MIT License