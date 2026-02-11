# Obsidian Official CLI Skill

An OpenClaw skill for working with Obsidian vaults using the official Obsidian CLI (v1.12+).

## ✨ Features

- **File Operations**: Create, read, edit, move, and delete notes from the terminal
- **Search & Discovery**: Full-text search, tag management, link analysis
- **Daily Notes & Tasks**: Manage daily notes and task lists via CLI
- **Templates & Bookmarks**: Work with templates and bookmark management
- **Plugin Management**: Install, enable, disable, and reload plugins
- **Sync & History**: Obsidian Sync operations and file version control
- **Developer Tools**: Console debugging, DOM inspection, screenshots
- **TUI Mode**: Interactive terminal UI with autocomplete and history

## 📋 Requirements

- **Obsidian 1.12+** with early access
- **Catalyst license** (required for CLI access)
- **CLI enabled** in Obsidian settings: Settings → General → Command line interface → Enable

## 🚀 Installation

1. Download the skill file: [`obsidian-official-cli.skill`](obsidian-official-cli.skill)
2. Install via OpenClaw CLI:
   ```bash
   openclaw skills install obsidian-official-cli.skill
   ```

## 💡 Usage Examples

Once installed, the skill will automatically trigger when you mention Obsidian operations:

- "Create a new note called 'Meeting Notes' in my Obsidian vault"
- "Search for all notes containing 'project' in my vault"
- "Show me all incomplete tasks in my daily note"
- "List all plugins installed in Obsidian"
- "Take a screenshot of my current Obsidian workspace"

## 🛠️ Obsidian CLI Setup

1. **Upgrade to Obsidian 1.12+**: Get early access via insider builds
2. **Enable CLI**: Settings → General → Command line interface → Enable
3. **Register command**: Follow the prompt to add `obsidian` to your PATH
4. **Restart terminal**: Or run `source ~/.zprofile` on macOS
5. **Test setup**: Run `obsidian version`

**Note**: Obsidian must be running for CLI commands to work.

## 🔧 Supported Commands

The skill covers the complete Obsidian CLI command set:

### File Management
- Create, read, edit notes
- Move, rename, delete files
- Folder operations

### Content Operations  
- Search with filters and context
- Daily notes management
- Task list operations
- Property (frontmatter) management

### Vault Analysis
- Backlinks and outgoing links
- Orphaned notes detection
- Broken link identification
- Tag analysis

### Workspace & Plugins
- Plugin installation and management
- Theme and CSS snippet control
- Workspace layout management
- Command palette access

### Advanced Features
- Obsidian Sync operations
- File history and versioning
- Developer tools and debugging
- Mobile device emulation

## 🎮 TUI Mode

The skill supports Obsidian's interactive Terminal UI mode with:
- Command autocomplete
- Command history with search
- Keyboard shortcuts
- Multi-command sessions

## 📚 Documentation

The skill includes comprehensive documentation covering:
- Command syntax and parameters
- File targeting patterns (`file=` vs `path=`)
- TUI keyboard shortcuts
- Platform-specific setup instructions
- Troubleshooting guides

## 🤝 Contributing

Found an issue or want to improve the skill? 

1. Open an issue describing the problem/enhancement
2. Fork the repository
3. Make your changes to the skill
4. Submit a pull request

## 📄 License

MIT License - feel free to modify and redistribute.

## 🔗 Links

- [Obsidian Official CLI Documentation](https://help.obsidian.md/cli)
- [OpenClaw Documentation](https://docs.openclaw.ai)
- [ClawHub - Skill Marketplace](https://clawhub.com)

---

**Built for OpenClaw** 🦞 | **Supports Obsidian CLI v1.12+** 📝