# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub Pages site repository for Ajnunna Systems LLC containing industry insights and reports. The repository serves as both the source and publication platform for research-based content focused on streaming operations and technology insights.

## Architecture & Structure

- **Simple Markdown-based Documentation**: The repository contains markdown files with industry reports and insights
- **Single Document Focus**: Currently contains one primary document: `20250723-operators-streaming-insights-2025.md`
- **Minimal Configuration**: No build tools, package managers, or complex infrastructure - just git-tracked markdown files
- **Publication Ready**: Documents are structured for direct publication or sharing with industry professionals

## File Structure

```
/
├── .gitignore                                      # Standard git ignore (currently only .DS_Store)
├── 20250723-operators-streaming-insights-2025.md  # Main industry report on streaming operations
└── CLAUDE.md                                       # This file
```

## Content Guidelines

When working with documents in this repository:

- **Industry Focus**: Content centers on streaming operations, technology insights, and industry analysis
- **Professional Audience**: Documents target technical professionals in streaming/media operations
- **Research-Based**: Content includes data, quotes, and industry references
- **Anonymous Sources**: Maintains anonymity of industry professionals and companies when sharing insights
- **Structured Format**: Uses consistent markdown formatting with clear sections, tables, and quotes

## Common Operations

This is a GitHub Pages site with Jekyll processing:

- **Local development**: `bundle exec jekyll serve` (requires Ruby/Jekyll setup)
- **View site**: GitHub Pages automatically builds and deploys on push to main
- **Edit documents**: Direct markdown editing (Jekyll processes automatically)
- **Version control**: Standard git operations
- **Site structure**: Uses Jekyll with `_config.yml` for configuration

## Working with Content

- Maintain professional tone and industry focus when editing
- Preserve anonymity of sources and companies mentioned
- Keep formatting consistent with existing document structure
- Ensure citations and references are properly maintained
- **No LICENSE file**: License information is included at the end of each markdown file
- **License format**: End each document with author, date, and CC BY-SA 4.0 licensing block:
  ```markdown
  ---
  
  **Author:** Ajnunna Systems LLC  
  **Date:** [Publication Date]
  
  [Document Title](https://ajnunnasystems.github.io/ajnunna-public-docs) © 2025 by [Ajnunna Systems LLC](https://github.com/orgs/ajnunna-systems) is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 
  
  ![CC](https://mirrors.creativecommons.org/presskit/icons/cc.svg) 
  ![BY](https://mirrors.creativecommons.org/presskit/icons/by.svg)
  ![SA](https://mirrors.creativecommons.org/presskit/icons/sa.svg)
  ```
- **GitHub Pages**: CLAUDE.md is excluded from site build via _config.yml exclude list