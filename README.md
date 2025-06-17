# VS Code Settings

This repository contains my personal VS Code settings configuration for optimal development experience.

## Overview

These settings are optimized for:

- **Frontend Development** (React, TypeScript, JavaScript)
- **Enhanced Productivity** with Cursor AI assistance
- **Bilingual Support** (English & Persian/Farsi)

## Key Features

### 🎨 Visual Customization

- **Theme**: Bearded Theme Arc
- **Icons**: Material Icon Theme
- **Font**: Monaspace Neon with Vazir fallback
- **Font Size**: 13px with ligatures enabled

### ⚡ Editor Enhancements

- Smooth cursor animations
- Auto-closing brackets
- Word wrap enabled
- Linked editing for HTML/JSX
- Quick suggestions (disabled in comments)

### 🛠️ Language Support

- **TypeScript/JavaScript**: Prettier formatting
- **React**: Enhanced support with custom file labels
- **Tailwind CSS**: Emmet completions and conflict detection
- **JSON/YAML**: Prettier formatting

### 🔧 Productivity Features

- **Cursor AI**: Partial accepts and chat notifications
- **Git**: Streamlined workflow (no smart commit, auto sync)
- **File Management**: Custom labels for API routes, pages, and layouts
- **Spell Check**: Bilingual support (English & Persian)

### 📁 File Associations

- CSS files are associated with Tailwind CSS for better IntelliSense

### 🎯 Custom File Labels

- API routes: `api - {directory} - {filename}`
- Pages: `Page - {directory}`
- Layouts: `Layout - {directory}`

## Installation

1. Clone or download this repository
2. Copy the `settings.json` file to your VS Code settings directory:
   - **Windows**: `%APPDATA%\Code\User\settings.json`
   - **macOS**: `~/Library/Application Support/Code/User/settings.json`
   - **Linux**: `~/.config/Code/User/settings.json`

## Required Extensions

For optimal experience, install these extensions:

- **Prettier - Code formatter** (`esbenp.prettier-vscode`)
- **Material Icon Theme** (`PKief.material-icon-theme`)
- **Tailwind CSS IntelliSense** (`bradlc.vscode-tailwindcss`)

## Font Setup

The settings use Monaspace Neon font. To install:

1. Download Monaspace fonts from [GitHub](https://github.com/githubnext/monaspace)
2. Install the fonts on your system
3. VS Code will automatically use them

## Notes

- Telemetry is enabled for Red Hat extensions
- JSON schema downloads are enabled for better IntelliSense
- TypeScript imports are automatically updated on file moves
