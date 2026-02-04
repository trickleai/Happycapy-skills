# Happycapy Skills

A curated collection of high-quality Claude Code skills to enhance your development workflow. Skills are organized by category for easy discovery.

## 📚 Browse by Category

### 🎨 Content Creation
Skills for creating engaging content across different platforms.

- **[Reddit Post Writer](content-creation/reddit-post-writer/)** - Generate authentic Reddit posts that sound human, avoid AI detection, and spark engagement across 25+ subreddits. Includes 7-persona committee review system and subreddit-specific guidelines. ([Original](https://github.com/niveshdandyan/reddit-post-skill))

### 📊 Presentation
Skills for creating stunning presentations and visual content.

- **[Frontend Slides](presentation/frontend-slides/)** - Create animation-rich HTML presentations from scratch or convert PowerPoint files. Zero dependencies, 12 distinctive design presets, responsive and viewport-fitted. ([Original](https://github.com/zarazhangrui/frontend-slides))

### 💻 Development
_Coming soon - Skills for code generation, debugging, and development workflows._

### ⚡ Productivity
_Coming soon - Skills for automation, task management, and efficiency._

### 📈 Data Analysis
_Coming soon - Skills for data processing, visualization, and insights._

### 🎨 Design
_Coming soon - Skills for UI/UX design, graphics, and visual assets._

---

## Installation

### For Claude Code Users

Clone this repository and install individual skills:

```bash
# Clone the repository
git clone https://github.com/trickleai/Happycapy-skills.git
cd Happycapy-skills

# Install a specific skill (example: Reddit Post Writer)
mkdir -p ~/.claude/skills
cp -r content-creation/reddit-post-writer ~/.claude/skills/

# Or install Frontend Slides
cp -r presentation/frontend-slides ~/.claude/skills/

# Or install all skills from a category
cp -r content-creation/* ~/.claude/skills/
```

### Repository Structure

```
Happycapy-skills/
├── content-creation/       # Content creation skills
│   └── reddit-post-writer/
├── presentation/          # Presentation skills
│   └── frontend-slides/
├── development/           # Development tools (coming soon)
├── productivity/          # Productivity tools (coming soon)
├── data-analysis/         # Data analysis (coming soon)
└── design/               # Design tools (coming soon)
```

Each skill follows the standard Claude Code skill structure with its own SKILL.md and reference materials.

---

## About This Collection

Happycapy Skills is a curated collection of the best Claude Code skills for developers, content creators, and professionals. Each skill is:
- Thoroughly tested and production-ready
- Well-documented with examples
- Actively maintained and updated
- Designed to integrate seamlessly with Claude Code

## Contributing

We welcome contributions! If you have a skill you'd like to add to this collection:
1. Fork this repository
2. Add your skill in a dedicated folder
3. Include comprehensive documentation
4. Submit a pull request

Please ensure your skill follows Claude Code best practices and includes:
- Clear SKILL.md file
- Usage examples
- Any necessary reference materials
- License information

## License

Each skill in this collection maintains its original license. Please refer to individual skill directories for specific license information.

---

**Repository:** [github.com/trickleai/Happycapy-skills](https://github.com/trickleai/Happycapy-skills)

**Maintained by:** [Trickle AI](https://github.com/trickleai)
