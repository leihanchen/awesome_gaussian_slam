# Contributing to Awesome Gaussian SLAM Resources

Thank you for your interest in contributing to this curated list of Gaussian SLAM resources! This document provides guidelines for contributing to ensure consistency and quality.

## 🚫 Branch Protection Policy

**IMPORTANT**: This repository has strict branch protection rules in place:

- **Direct pushes to the `master` branch are prohibited** for all contributors except repository administrators
- **All contributions must be made via Pull Requests**
- **Pull requests require approval** from repository maintainers before merging
- **Only administrators can force push** to the master branch

### Why These Rules?

1. **Quality Control**: All changes are reviewed before being merged
2. **Prevent Accidents**: Protects against accidental deletions or malformed content
3. **Maintain History**: Preserves a clean git history with meaningful commits
4. **Collaboration**: Encourages discussion and feedback on changes

## 🔄 Contribution Workflow

### 1. Fork and Clone
```bash
# Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/awesome_gaussian_slam.git
cd awesome_gaussian_slam
```

### 2. Create a Feature Branch
```bash
# Create and switch to a new branch
git checkout -b add-new-paper-title
# or
git checkout -b fix-broken-links
```

### 3. Make Your Changes
Follow the guidelines below for different types of contributions.

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add: New paper on Gaussian SLAM optimization"
```

### 5. Push to Your Fork
```bash
git push origin your-branch-name
```

### 6. Create a Pull Request
- Go to the original repository on GitHub
- Click "New Pull Request"
- Select your branch and provide a clear description
- Use the provided PR template

## 📝 Types of Contributions

### Adding New Papers/Resources

When adding new papers or resources, please ensure:

1. **Relevance**: The content must be related to Gaussian SLAM, 3D Gaussian Splatting, or closely related topics
2. **Quality**: Prefer peer-reviewed papers, well-documented code, and established resources
3. **Completeness**: Include as many relevant links as possible (paper, code, project page, demo)
4. **Recency**: Prioritize recent work, but historically significant papers are also welcome

### Format for New Entries

Use this format for new paper entries:
```markdown
- **[Conference/Journal' Year] Paper Title**, Authors et al., Publication Year | [📄 Paper](link) | [🌐 Project Page](link) | [💻 Code](link) | [🤗 Demo](link) | [🎥 Video](link)
```

Example:
```markdown
- **[SIGGRAPH' 23] 3D Gaussian Splatting for Real-Time Radiance Field Rendering**, Kerbl et al., SIGGRAPH 2023 | [📄 Paper](https://arxiv.org/abs/2308.04079) | [🌐 Project Page](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [💻 Code](https://github.com/graphdeco-inria/gaussian-splatting)
```

### Section Guidelines

#### Papers by Year
- Place new papers in the appropriate year section (2025, 2024, etc.)
- Within each year, organize by category (Gaussian SLAM, 3D Reconstruction, etc.)
- List papers chronologically within each category (newest first)

#### Categories
- **Gaussian SLAM**: Papers specifically about SLAM systems using Gaussian representations
- **Gaussian Optimization**: Papers about optimizing Gaussian representations
- **Navigation**: Papers about navigation using Gaussian maps
- **Poses**: Papers about pose estimation with Gaussians
- **Large Scale**: Papers about large-scale Gaussian-based systems
- **3D Reconstruction**: Papers about 3D reconstruction using Gaussians
- **3D Generations**: Papers about generating 3D content with Gaussians

### Link Guidelines

1. **Paper Links**: Prefer official publication links, then arXiv
2. **Code Links**: Direct links to GitHub repositories or official code releases
3. **Project Pages**: Official project websites or author pages
4. **Demos**: Interactive demos, Hugging Face spaces, or online viewers
5. **Videos**: YouTube videos, conference presentations, or supplementary material

## ✅ Quality Standards

### Before Submitting

1. **Test All Links**: Ensure all links work and point to the correct resources
2. **Check for Duplicates**: Search the document to avoid duplicate entries
3. **Verify Information**: Double-check paper titles, author names, and publication details
4. **Follow Format**: Use the exact format specified above
5. **Proper Categorization**: Place entries in the most appropriate section

### Content Guidelines

1. **No Promotional Content**: Avoid overly promotional language
2. **Objective Descriptions**: Keep descriptions factual and neutral
3. **English Only**: All content should be in English
4. **Academic Focus**: Prioritize academic papers and research projects
5. **Open Access Preferred**: When possible, prefer open-access resources

## 🐛 Reporting Issues

### Bug Reports
Use the bug report template for:
- Broken links
- Formatting issues
- Duplicate entries
- Incorrect categorization
- Outdated information

### Feature Requests
Use the feature request template for:
- New sections or categories
- Improved organization
- Additional metadata
- Enhanced formatting

## 📋 Pull Request Guidelines

### PR Title Format
- `Add: [Paper/Resource Title]` for new additions
- `Fix: [Brief description]` for bug fixes
- `Update: [Brief description]` for updates
- `Reorganize: [Brief description]` for structural changes

### PR Description
- Use the provided PR template
- Clearly describe what you're adding or changing
- Include links to verify the resources
- Mention any special considerations

### Review Process

1. **Automated Checks**: GitHub Actions will run basic validation
2. **Manual Review**: Maintainers will review content quality and accuracy
3. **Feedback**: You may receive requests for changes
4. **Approval**: Once approved, your PR will be merged

## 🤝 Community Guidelines

### Be Respectful
- Be respectful to all contributors and maintainers
- Provide constructive feedback
- Help newcomers understand the guidelines

### Be Patient
- Reviews may take time due to the volunteer nature of maintenance
- Be patient with the review process
- Respond promptly to feedback when possible

### Be Collaborative
- Discuss major changes before implementing
- Consider alternative approaches suggested by reviewers
- Help improve others' contributions when possible

## ❓ Questions?

If you have questions about contributing:

1. Check this document first
2. Look at existing issues and PRs for examples
3. Create a new issue with your question
4. Tag maintainers if needed

## 🙏 Recognition

All contributors are valued and recognized:
- Contributors are listed in the repository
- Significant contributions may be highlighted in releases
- Credit is given for major improvements or additions

---

Thank you for helping make this resource valuable for the Gaussian SLAM community! 🎉