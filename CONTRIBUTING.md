# 🤝 Contributing to Tech News Hub

Thank you for your interest in contributing to Tech News Hub! This repository thrives on community contributions.

[🇺🇸 English](CONTRIBUTING.md) • [🇧🇷 Português](pt-BR/CONTRIBUTING.md) • [🇪🇸 Español](es/CONTRIBUTING.md)

---

## 📋 Table of Contents

- [How to Contribute](#how-to-contribute)
- [Contribution Guidelines](#contribution-guidelines)
- [Adding a New Source](#adding-a-new-source)
- [Suggesting a New Category](#suggesting-a-new-category)
- [Reporting Broken Links](#reporting-broken-links)
- [Code of Conduct](#code-of-conduct)

---

## 🚀 How to Contribute

1. **Fork the Repository**
   ```bash
   git clone https://github.com/yourusername/tech-news-hub.git
   cd tech-news-hub
   ```

2. **Create a New Branch**
   ```bash
   git checkout -b add-new-source
   ```

3. **Make Your Changes**
   - Add sources to appropriate category files
   - Follow the format guidelines below
   - Test all links to ensure they work

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add [Source Name] to [Category]"
   ```

5. **Push and Create PR**
   ```bash
   git push origin add-new-source
   ```
   Then create a Pull Request on GitHub

---

## ✅ Contribution Guidelines

### Quality Standards

**✅ DO Include:**
- High-quality, reputable sources
- Active blogs/sites (updated in last 6 months)
- Free or freemium content
- English language sources (primarily)
- Clear, accurate descriptions
- Working links

**❌ DON'T Include:**
- Promotional or spam content
- Paywalled content (unless clearly noted)
- Inactive blogs (6+ months without updates)
- Personal blogs without substantial content
- Duplicate sources already listed
- Affiliate links (unless disclosed)

---

## 📝 Adding a New Source

### Format Template

When adding a source, use this markdown format:

**For tables:**
```markdown
| [Source Name](https://example.com/) | Brief description of content | Update Frequency |
```

**For lists:**
```markdown
- [Source Name](https://example.com/) - Description of what makes it valuable
```

### Example Addition

```markdown
## 📰 News Sites

### New Section (if needed)

| Source | Description | Update Frequency |
|--------|-------------|------------------|
| [TechCrunch](https://techcrunch.com/) | Startup and technology news | Daily |
| [The Verge](https://www.theverge.com/) | Technology and digital culture | Daily |
```

---

## 🗂️ Suggesting a New Category

If you think we're missing an important category:

1. **Open an Issue** with:
   - Category name
   - Brief description
   - Why it's needed
   - At least 10-15 quality sources for the category

2. **Use This Template:**

```markdown
## New Category Suggestion

**Category Name:** [e.g., Quantum Computing]

**Description:** [What this category covers]

**Why Needed:** [Justify the new category]

**Initial Sources:**
1. [Source 1](url) - Description
2. [Source 2](url) - Description
...
```

---

## 🔗 Reporting Broken Links

Found a broken link? Help us fix it!

1. **Open an Issue** titled: "Broken Link: [Source Name]"
2. **Include:**
   - Link that's broken
   - Category/file where it's located
   - Suggested replacement (if available)

**Or** Submit a PR with the fix directly!

---

## 📂 File Structure

```
tech-news-hub/
├── README.md
├── CONTRIBUTING.md
├── categories/
│   ├── software-development.md
│   ├── ai-ml.md
│   ├── cloud-devops.md
│   └── ... (other categories)
├── formats/
│   ├── newsletters.md
│   ├── podcasts.md
│   └── ... (content types)
└── frequency/
    ├── daily.md
    └── ... (update frequencies)
```

---

## 🎯 Best Practices

### When Adding Sources

1. **Verify the Link** - Make sure it works
2. **Check for Duplicates** - Search the file first
3. **Use Proper Formatting** - Follow markdown standards
4. **Write Clear Descriptions** - Help users understand the value
5. **Place in Right Category** - Use the most appropriate section
6. **Maintain Alphabetical Order** - Within subsections when possible

### Description Guidelines

**Good Description:**
```markdown
- [Martin Fowler's Blog](https://martinfowler.com/) - In-depth articles on software design, architecture patterns, and refactoring by renowned author
```

**Poor Description:**
```markdown
- [Martin Fowler's Blog](https://martinfowler.com/) - Blog about coding
```

---

## 🌟 Recognition

Contributors will be:
- Acknowledged in our [Contributors section](#) (coming soon)
- Mentioned in release notes for significant contributions
- Part of building a valuable resource for the developer community!

---

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inclusive experience for everyone.

### Expected Behavior

- Be respectful and constructive
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy towards others

### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Spam or promotional abuse
- Publishing others' private information

---

## 💬 Questions?

- Open an [issue](https://github.com/yourusername/tech-news-hub/issues)
- Start a [discussion](https://github.com/yourusername/tech-news-hub/discussions)
- Reach out to maintainers

---

## 🙏 Thank You!

Every contribution, no matter how small, helps make Tech News Hub better for everyone. Thank you for being part of this project!

---

[⬆ Back to Top](#-contributing-to-tech-news-hub) | [🏠 Home](README.md)
