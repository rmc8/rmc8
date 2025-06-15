# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **personal GitHub profile repository** for rmc8 (K), an Amazon Risk Manager based in Tokyo. The repository serves as a professional showcase with:

- **83 public repositories** demonstrating diverse technology exploration
- **5+ years of active GitHub contribution** since April 2019
- **Multilingual development capabilities** (Japanese, English, Korean)
- **Cross-platform expertise** spanning web, mobile, and desktop applications

The main content is a comprehensive profile README.md that displays on the GitHub profile page.

## Current Active Projects

### 🍱 **Gourmet Journey JP** (Svelte)

A comprehensive Japanese regional gourmet management application covering all 47 prefectures' local specialties and mail-order system.

### 🦋 **moodeSky** (Dart/Flutter)

A feature-rich Bluesky client application with enhanced user experience and modern mobile interface.

### 📝 **Astro Blog** (Astro)

Personal multilingual blog platform supporting Japanese, English, and Korean content with modern static site generation.

### 🦀 **Raspberry Pi IoT Projects** (Rust)

Experimenting with IoT development using Rust on Raspberry Pi for learning systems programming.

## Technical Stack Overview

### Primary Languages (by repository distribution)

- **Python**: 59% (49 repos, 370KB codebase) - Main language for data analysis, automation, and backend
- **JavaScript**: 12% (3 repos, full-stack projects)
- **Dart**: 6% (5 repos, Flutter mobile development)
- **TypeScript**: 5% (modern web development)
- **Rust**: 2% (systems programming learning)

### Key Technologies

- **Frontend & Web**: Astro, Svelte, TailwindCSS, FastAPI
- **Mobile & Cross-Platform**: Flutter/Dart, Tauri
- **AI & Machine Learning**: LangChain, LangGraph, Ollama
- **Infrastructure**: MCP (Model Context Protocol), GitHub Actions, Vercel

## Development Philosophy

- **Learning-driven development** with emphasis on modern technologies
- **Quality over quantity** approach to project architecture
- **Cross-platform thinking** for maximum accessibility
- **Open source contribution** mindset with MIT licensing
- **Continuous experimentation** with emerging frameworks

## MCP Configuration

The repository includes MCP (Model Context Protocol) server configuration in `.mcp.json`:

- **GitHub MCP Server**: Configured to connect to GitHub Copilot API using personal access token
- **Sequential Thinking Server**: NPX-based server for enhanced reasoning capabilities

### Environment Setup

1. Copy `.env.example` to `.env`
2. Set `GITHUB_PERSONAL_ACCESS_TOKEN` with a valid GitHub personal access token
3. The `.env` file is gitignored for security

## External Links & Social Presence

- **Portfolio**: [rmc-8.com](https://rmc-8.com) - Personal website with multilingual blog
- **Bluesky**: [@k.rmc-8.com](https://bsky.app/profile/k.rmc-8.com) - Active social presence
- **X (Twitter)**: [@rmc_km](https://twitter.com/rmc_km) - Technical updates and insights

## README.md Maintenance Guidelines

When updating the profile README.md:

1. **Maintain Professional Tone**: Balance personal passion with professional credibility
2. **Technical Accuracy**: Only include technologies actually used, not just framework dependencies
3. **Current Project Focus**: Highlight active development work with specific descriptions
4. **Multilingual Approach**: Acknowledge Japanese, English, and Korean capabilities
5. **Open Source Emphasis**: Stress MIT licensing and collaboration openness
6. **Visual Elements**: Maintain GitHub stats integration for dynamic content
7. **Contact Information**: Ensure all links are current and professional

## Markdown Style Guidelines

This repository uses markdownlint for consistent formatting. Follow these rules:

### Heading Structure

- Use proper heading hierarchy: `#`, `##`, `###`, `####`
- **AVOID**: Using bold text (`**text**`) as pseudo-headings
- **CORRECT**: Use appropriate heading levels instead

```markdown
❌ **Technology Stack**
✅ ### Technology Stack

❌ **Frontend & Web**
✅ #### Frontend & Web
```

### Emphasis Style

- Use **underscores** for emphasis, not asterisks
- **AVOID**: `*italic*` and `**bold**`
- **CORRECT**: `_italic_` and `__bold__`

```markdown
❌ *"Quote text"*
✅ _"Quote text"_
```

### List Formatting

- Add blank lines around lists
- Add blank lines around headings
- Add blank lines around code blocks

```markdown
❌ 
## Heading
- List item
```

```markdown
✅ 
## Heading

- List item
```

### Code Blocks

- Always specify language for syntax highlighting
- Add blank lines before and after code blocks

```markdown
❌ ```text
code here
```

✅ 

```text
code here
```

```

### File Endings

- Always end files with a single newline character
- Remove trailing whitespace

### Common markdownlint Rules to Follow

- **MD022**: Headings should be surrounded by blank lines
- **MD032**: Lists should be surrounded by blank lines
- **MD036**: Don't use emphasis as headings
- **MD040**: Specify language for fenced code blocks
- **MD047**: Files should end with single newline
- **MD049**: Use consistent emphasis style (underscores)

## Key Files

- `README.md`: Professional GitHub profile showcase (English)
- `.mcp.json`: MCP server configuration for development tools
- `.env.example`: Environment variable template for GitHub integration
- `.gitignore`: Security configuration for sensitive files
