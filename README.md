# Ajnunna Systems LLC - Public Documentation

This repository contains public documentation, industry insights, and reports from Ajnunna Systems LLC, focused on streaming operations and technology.

## 🌐 Live Site

The documentation is published at: **https://ajnunna-systems.github.io/ajnunna-public-docs**

## 📁 Repository Structure

```
├── 20250723-operators-streaming-insights-2025.md  # Industry reports
├── index.md                                        # Homepage
├── _config.yml                                     # Jekyll configuration
├── assets/
│   └── css/
│       └── main.scss                               # Custom styling
├── _sass/
│   └── custom.scss                                 # SCSS partials
├── CLAUDE.md                                       # AI assistant guidelines
├── Gemfile                                         # Ruby dependencies
├── docker-compose.yml                              # Docker development setup
└── README.md                                       # This file
```

## 🚀 Local Development

### Option 1: Docker (Recommended - Most Secure)

**Requirements:** Docker Desktop

```bash
# Start development server
docker-compose up

# View site at http://localhost:4001/ajnunna-public-docs
```

### Option 2: Native Ruby/Jekyll

**Requirements:** Ruby 2.7+ (avoid system Ruby on macOS)

```bash
# Install dependencies
bundle install --path vendor/bundle

# Start development server
bundle exec jekyll serve --baseurl "/ajnunna-public-docs"

# View site at http://localhost:4000/ajnunna-public-docs
```

### Option 3: VS Code Extension

1. Install "Jekyll Run" extension
2. Open Command Palette (`Cmd+Shift+P`)
3. Run "Jekyll: Serve"

## 📝 Content Guidelines

### Document Format

All documents should follow this structure:

```markdown
---
layout: default
title: "Your Document Title"
---

# Your Document Title

[Content here...]

---

**Author:** Ajnunna Systems LLC  
**Date:** [Publication Date]

<div class="license-section">

**[Document Title]({{ "/" | relative_url }}) © 2025 by [Ajnunna Systems LLC](https://github.com/orgs/ajnunna-systems)** is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="CC" style="height: 1.2em; margin: 0 0.2em; vertical-align: middle;">
<img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="BY" style="height: 1.2em; margin: 0 0.2em; vertical-align: middle;">
<img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="SA" style="height: 1.2em; margin: 0 0.2em; vertical-align: middle;">

</div>
```

### Content Principles

- **Professional Focus**: Industry insights and technical analysis
- **Anonymous Sources**: Protect individual and company identities
- **Data-Driven**: Include research, quotes, and industry references
- **CC BY-SA 4.0 Licensed**: All content must include proper licensing

## 🛠️ Technical Details

### GitHub Pages Configuration

- **Framework**: Jekyll with Minima theme
- **Styling**: Custom SCSS in `_sass/custom.scss`
- **Deployment**: Automatic via GitHub Pages on push to `main`
- **Custom Domain**: Not configured (uses github.io subdomain)

### Key Files

- `_config.yml`: Site configuration, plugins, and metadata
- `assets/css/main.scss`: Main stylesheet importing theme and custom styles
- `_sass/custom.scss`: Custom styling and theme overrides
- `CLAUDE.md`: Guidelines for Claude Code AI assistant (excluded from site)

### Excluded Files

The following files are tracked in git but excluded from the built site:

- `CLAUDE.md` - AI assistant guidelines
- `Gemfile*` - Ruby dependencies
- `vendor/` - Local Ruby gems
- `docker-compose.yml` - Development configuration

## 🔒 Security & Dependencies

### Ruby Gems

Dependencies are managed via Bundler and installed locally to avoid system-wide changes:

```bash
bundle install --path vendor/bundle
```

### Docker Security

The Docker setup uses:
- Official Jekyll image
- Non-root user execution
- Local volume mounts only
- No sensitive environment variables

## 📄 License

All content in this repository is licensed under [Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) unless otherwise noted.

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch
3. **Follow** the content guidelines above
4. **Test** locally using Docker or Jekyll
5. **Submit** a pull request

### For Content Contributors

- Use the established document format
- Include proper CC BY-SA 4.0 licensing
- Maintain professional tone and anonymize sources
- Test changes locally before submitting

## 📧 Contact

- **Organization**: [Ajnunna Systems LLC](https://github.com/orgs/ajnunna-systems)
- **Email**: contact@ajnunnasystems.com
- **Website**: https://ajnunna-systems.github.io/ajnunna-public-docs

---

**Repository maintained by:** Ajnunna Systems LLC  
**Last updated:** July 23, 2025