# Contributing to Public Health Data Catalog

Thank you for your interest in contributing to the Public Health Data Catalog! This document provides guidelines for contributing to this educational resource.

## 🎯 Ways to Contribute

### 1. Adding New Data Sources

We welcome additions of authoritative public health data sources!

**Before Adding:**
- Ensure the source is from a reputable organization (government agency, international org, academic institution)
- Verify the data is publicly accessible
- Check that the source isn't already listed

**How to Add:**

1. Fork the repository
2. Open `public_health_data_catalog.html` in a text editor
3. Find the appropriate category section
4. Add your data source following this template:

```html
<div class="resource-item">
    <h4 class="resource-title">
        <a href="https://example.org/" target="_blank">Your Data Source Name</a>
    </h4>
    <div class="resource-url">
        <a href="https://example.org/" target="_blank">https://example.org/</a>
    </div>
    <p class="resource-description">
        A concise description (2-3 sentences) of what the data source provides, 
        including key features, coverage, and data types available.
    </p>
</div>
```

5. Ensure the parent `<div class="category-card">` has the correct `data-category` attribute:
   - `global` - International organizations
   - `us-federal` - US federal agencies
   - `disease` - Disease-specific platforms
   - `surveillance` - Surveillance and monitoring
   - `genomic` - Genomic/molecular data
   - `api` - APIs and programmatic access

6. Test the search and filter functionality
7. Submit a pull request

### 2. Reporting Issues

Found a problem? Let us know!

**Types of Issues:**
- 🔗 Broken links
- 📝 Incorrect information
- 🐛 Bugs or display issues
- 💡 Feature suggestions
- 📚 Documentation improvements

**How to Report:**

1. Check if the issue already exists
2. Create a new issue with:
   - Clear, descriptive title
   - Detailed description
   - Steps to reproduce (for bugs)
   - Screenshots (if relevant)
   - Browser/device info (for display issues)

### 3. Updating Existing Sources

Data sources change over time. Help us keep information current!

**What to Update:**
- Broken or redirected URLs
- Outdated descriptions
- Changed organization names
- New features or capabilities
- Updated statistics

**How to Update:**
1. Fork the repository
2. Make your changes
3. Document what you changed in the PR description
4. Submit a pull request

### 4. Improving Documentation

Documentation improvements are always welcome!

**Areas to Improve:**
- README clarity
- Installation instructions
- Usage examples
- Code comments
- Educational materials

## 📋 Contribution Guidelines

### Quality Standards

**Data Sources Must:**
- ✅ Be from authoritative, reputable organizations
- ✅ Provide publicly accessible data
- ✅ Be actively maintained (check for recent updates)
- ✅ Have clear documentation
- ✅ Be relevant to public health research/practice

**Descriptions Should:**
- ✅ Be concise (2-3 sentences)
- ✅ Use active voice
- ✅ Include key statistics where relevant
- ✅ Avoid marketing language
- ✅ Be factually accurate

### Code Style

**HTML:**
- Use consistent indentation (4 spaces)
- Include descriptive comments for sections
- Maintain existing structure and naming conventions
- Validate HTML before submitting

**CSS:**
- Follow existing naming patterns
- Group related styles together
- Comment complex animations or effects
- Maintain responsive design principles

**JavaScript:**
- Use clear, descriptive variable names
- Include comments for complex logic
- Test across major browsers
- Maintain vanilla JS (no frameworks)

### Commit Messages

Use clear, descriptive commit messages:

**Good:**
```
Add WHO Mortality Database to Global Organizations section
Update ECDC Atlas URL (redirected to new domain)
Fix search functionality for special characters
```

**Avoid:**
```
Update
Fix stuff
Changes
```

### Pull Request Process

1. **Fork & Create Branch**
   ```bash
   git checkout -b feature/add-new-source
   # or
   git checkout -b fix/broken-link
   ```

2. **Make Changes**
   - Follow style guidelines
   - Test thoroughly
   - Update documentation if needed

3. **Commit**
   ```bash
   git add .
   git commit -m "Add [Source Name] to [Category] section"
   ```

4. **Push**
   ```bash
   git push origin feature/add-new-source
   ```

5. **Create Pull Request**
   - Provide clear description
   - Reference any related issues
   - Include testing details

6. **Review Process**
   - Maintainer will review within 1 week
   - Address any requested changes
   - PR will be merged once approved

## 🧪 Testing Checklist

Before submitting, verify:

- [ ] Links work correctly (all URLs clickable)
- [ ] Search finds your addition
- [ ] Filters work with your data-category
- [ ] Description is clear and accurate
- [ ] No typos or grammatical errors
- [ ] Mobile responsive (test on small screen)
- [ ] Works in Chrome, Firefox, Safari, Edge
- [ ] HTML validates (use W3C validator)

## 🎨 Design Principles

When contributing, maintain these design principles:

1. **Simplicity**: Single-file, no build process
2. **Accessibility**: Works without JavaScript fallbacks
3. **Performance**: Fast loading, minimal dependencies
4. **Usability**: Intuitive search and navigation
5. **Aesthetics**: Consistent futuristic design

## ❓ Questions?

Not sure about something? Here's how to get help:

- 📧 Email: [Your email]
- 💬 Open a discussion on GitHub
- 📖 Check existing issues for similar questions
- 📚 Review the README thoroughly

## 🏆 Recognition

Contributors will be:
- Listed in README acknowledgments
- Credited in commit history
- Appreciated by students and researchers worldwide!

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inclusive experience for everyone, regardless of:
- Age
- Body size
- Disability
- Ethnicity
- Gender identity and expression
- Level of experience
- Nationality
- Personal appearance
- Race
- Religion
- Sexual identity and orientation

### Expected Behavior

- Use welcoming and inclusive language
- Be respectful of differing viewpoints
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy toward others

### Unacceptable Behavior

- Trolling, insulting comments, or personal attacks
- Public or private harassment
- Publishing others' private information
- Other conduct inappropriate in a professional setting

### Enforcement

Violations may result in:
1. Warning
2. Temporary ban from contributing
3. Permanent ban from the project

Report issues to: [Your email]

## 🎓 For Students

Special considerations for student contributors:

- **First PR?** We're here to help! Don't hesitate to ask questions.
- **Learning Git?** Mistakes are OK - we'll guide you through.
- **Class Assignment?** Mention it in your PR description.
- **Need Citation?** Use the citation format in README.

## 📊 Priority Areas

Current priorities for contributions:

1. **High Priority:**
   - Fixing broken links
   - Adding missing major data sources
   - Improving mobile responsiveness
   - Adding data quality indicators

2. **Medium Priority:**
   - Enhancing descriptions
   - Adding new categories
   - Improving accessibility
   - Documentation improvements

3. **Low Priority (but welcome!):**
   - Visual enhancements
   - Additional animations
   - Easter eggs
   - Localization prep

## 🔄 Update Cycle

- **Links**: Checked quarterly
- **Descriptions**: Reviewed annually
- **Design**: Updated as needed
- **New Sources**: Added as discovered

## 📅 Versioning

We use semantic versioning (MAJOR.MINOR.PATCH):

- **MAJOR**: Breaking changes to structure
- **MINOR**: New data sources or features
- **PATCH**: Bug fixes, link updates

## 🙏 Thank You!

Your contributions help students, researchers, and public health professionals worldwide access critical data sources. Every contribution, no matter how small, makes a difference.

**Together, we're building a more data-literate public health community!**

---

*Last updated: January 2026*
