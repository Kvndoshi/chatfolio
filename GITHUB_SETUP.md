# GitHub Setup Instructions

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `portfolio-sdk`
3. Description: "Add AI-powered chat to your portfolio in 1 line of code"
4. Set to **Public** (or Private if you prefer)
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Push to GitHub

Run these commands in the `portfoliosdk` directory:

```bash
# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfolio-sdk.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

## Step 3: Create GitHub Issues for TODO Items

After pushing, create GitHub Issues for each TODO item:

1. Go to https://github.com/YOUR_USERNAME/portfolio-sdk/issues
2. Click "New Issue"
3. Use the TODO items from `.github/ISSUE_TEMPLATE/todo.md` as reference

**Quick Issues to Create:**

### High Priority
- [ ] Vanilla JavaScript Implementation
- [ ] More Chat UI Templates
- [ ] Publish to NPM

### Medium Priority
- [ ] OpenRouter Conversation Memory Fix
- [ ] Button Placement Options
- [ ] Better Error Handling
- [ ] Documentation Improvements
- [ ] Testing Suite

### Low Priority
- [ ] Advanced Customization
- [ ] Performance Optimizations
- [ ] Security Enhancements

## Step 4: Add Repository Topics

On your GitHub repo page, click the gear icon next to "About" and add topics:
- `portfolio`
- `ai`
- `chat`
- `llm`
- `react`
- `typescript`
- `supermemory`
- `nextjs`

## Step 5: Update README Links

After creating the repo, update the README to replace `yourusername` with your actual GitHub username in the "Roadmap & TODO" section.

