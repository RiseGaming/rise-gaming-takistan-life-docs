# Contributing to Rise Gaming Takistan Life Documentation

Thank you for your interest in contributing to the Rise Gaming Takistan Life documentation! This guide will help you understand our process and standards for contributing to this repository.

## Table of Contents

- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Content Guidelines](#content-guidelines)
- [Contribution Workflow](#contribution-workflow)
- [Code Review Process](#code-review-process)
- [Documentation Standards](#documentation-standards)
- [Contact](#contact)

## Getting Started

This repository contains defensive documentation for Rise Gaming's Takistan Life Arma 3 gamemode, including:
- Player guides and tutorials
- Marketing materials
- Technical feature documentation
- Game mechanics reference

All content is designed to help players understand legitimate game mechanics and provide educational resources for the community.

## Repository Structure

```
├── README.md              # Main repository overview
├── CONTRIBUTING.md         # This file
├── CODEOWNERS             # Review assignments
├── CLAUDE.md              # AI assistant instructions
└── docs/
    ├── marketing/         # Promotional content
    │   └── AD_BRIEFS.md   # Marketing materials
    ├── player-guides/     # Player documentation
    │   └── USER_GUIDE.md  # Comprehensive player guide
    └── technical/         # Technical documentation
        ├── FEATURE_MAP.md # Feature overview matrices
        └── feature_catalog.json # Structured feature data
```

## Content Guidelines

### What We Accept
✅ **Player Education Content**
- Gameplay mechanic explanations
- Control references and tutorials  
- Economy and faction system guides
- Legal game feature documentation

✅ **Technical Documentation**
- Feature catalogs with code references
- Game balance information
- Server configuration details
- Maintenance and update documentation

✅ **Marketing Materials**
- Server promotion content
- Feature highlights
- Community engagement materials

### What We Don't Accept
❌ **Malicious Content**
- Exploits or cheating methods
- Server vulnerabilities
- Harmful modifications
- Content that violates game terms of service

❌ **Off-Topic Content**
- Non-Takistan Life related content
- Personal attacks or inappropriate material
- Copyright violations

## Contribution Workflow

### 1. Fork and Clone
```bash
git clone https://github.com/RiseGaming/rise-gaming-takistan-life-docs.git
cd rise-gaming-takistan-life-docs
```

### 2. Create a Feature Branch
```bash
git checkout -b feature/your-contribution-name
```

### 3. Make Your Changes
- Follow our [Documentation Standards](#documentation-standards)
- Test your changes locally
- Ensure accuracy with referenced codebase (commit 33b1595)

### 4. Commit Your Changes
```bash
git add .
git commit -m "Brief description of your changes

Detailed explanation of what was changed and why.
Reference any relevant issues or discussions."
```

### 5. Push and Create Pull Request
```bash
git push origin feature/your-contribution-name
```

Then create a pull request through GitHub with:
- Clear title describing the change
- Detailed description of what was modified
- Reference to any related issues
- Screenshots if applicable

## Code Review Process

### Automated Checks
- **Branch Protection**: Direct pushes to `main` are blocked
- **Required Reviews**: All changes require approval from code owners
- **Code Owners**: @pbmorris93, @TlZSp3ctr3, @tomwhite96

### Review Criteria
Reviewers will check for:
- **Accuracy**: Information matches the actual game implementation
- **Clarity**: Content is well-written and easy to understand
- **Completeness**: All necessary information is included
- **Consistency**: Formatting and style match existing documentation
- **Security**: No harmful or exploitative content

### Review Timeline
- Initial review: Within 2-3 business days
- Follow-up reviews: Within 1-2 business days after updates
- Urgent fixes: Same day review when possible

## Documentation Standards

### Markdown Formatting
- Use proper heading hierarchy (`#`, `##`, `###`)
- Include table of contents for longer documents
- Use code blocks for commands and configuration
- Add links to related sections and external resources

### Content Structure
- Start with clear overview/summary
- Use bullet points and numbered lists for clarity
- Include examples where applicable
- Provide cross-references to related features

### Code References
- Include file paths: `file_path:line_number`
- Reference commit SHA: 33b1595
- Explain why code sections are referenced
- Maintain accuracy with actual implementation

### Language and Tone
- Use clear, professional language
- Write for players of all experience levels
- Avoid jargon without explanation
- Maintain neutral, educational tone

## File-Specific Guidelines

### Player Guides (`docs/player-guides/`)
- Focus on practical, actionable information
- Include step-by-step instructions
- Provide control references and keybindings
- Explain game mechanics clearly

### Technical Documentation (`docs/technical/`)
- Maintain structured data integrity
- Update feature counts when adding content
- Include proper JSON formatting
- Cross-reference with other documentation

### Marketing Materials (`docs/marketing/`)
- Keep promotional tone while maintaining accuracy
- Highlight server features effectively
- Ensure claims are verifiable
- Maintain brand consistency

## Testing Your Changes

Before submitting:
1. **Spell Check**: Run spell check on all modified files
2. **Link Validation**: Ensure all internal links work
3. **Format Check**: Verify markdown renders correctly
4. **Accuracy Review**: Cross-check with game implementation
5. **Cross-References**: Update related documentation if needed

## Common Issues and Solutions

### Markdown Rendering Problems
- Check for proper heading formatting
- Ensure code blocks use correct syntax
- Validate bullet point indentation

### Broken Cross-References
- Update links when moving files
- Check relative path accuracy
- Verify section anchors exist

### Content Accuracy
- Reference the correct commit (33b1595)
- Verify feature descriptions with actual game
- Test procedures before documenting

## Contact

### Questions or Issues
- Create an issue on GitHub for documentation problems
- Tag @pbmorris93, @TlZSp3ctr3, or @tomwhite96 for urgent matters
- Use discussions for general questions

### Feature Requests
- Open an issue with the `enhancement` label
- Provide clear description of the requested addition
- Explain how it benefits the community

### Bug Reports
- Use the `bug` label for documentation errors
- Include specific location of the problem
- Suggest corrections when possible

---

## License and Attribution

By contributing to this repository, you agree that your contributions will be used for the educational and promotional purposes of the Rise Gaming Takistan Life server. All contributions should be original work or properly attributed.

Thank you for helping improve the Rise Gaming Takistan Life documentation! 🎮