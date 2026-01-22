# Demo Plugin Marketplace

This is a **demo/testing** marketplace for Claude Code plugins. It contains placeholder content to demonstrate and test the plugin marketplace functionality.

## Available Plugins

### hello-demo

A simple demo plugin that responds to greetings with a theatrical hello message.

**What it does:**
- Responds to "hello", "hi", or any greeting
- Uses a specific theatrical format with hat tips and bows
- Proves the plugin marketplace is working correctly

## Installation

### From Git Repository

```bash
# Step 1: Add the marketplace
/plugin marketplace add <your-git-repo-url>

# Step 2: Install the plugin
/plugin install hello-demo@demo-market
```

### From Local Path

```bash
# Install directly from local directory
claude plugin install /path/to/claude/plugins/hello-demo
```

## Usage

After installation, just say "hello" or "hi" and the skill will respond with:

```
*tips hat dramatically*

Well hello there, magnificent human!

I am the Hello Demo Skill, here to prove that this plugin marketplace is working splendidly!

May your code compile on the first try and your tests always pass!

*bows gracefully*
```

## Purpose

This marketplace exists for:
- Testing plugin installation workflows
- Demonstrating marketplace structure
- Validating skill auto-activation
- Learning how Claude Code plugins work

## Structure

```
claude/
├── .claude-plugin/
│   └── marketplace.json     # Marketplace manifest
├── plugins/
│   └── hello-demo/          # Demo plugin
│       ├── .claude-plugin/
│       │   └── plugin.json  # Plugin manifest
│       ├── skills/
│       │   └── hello-demo/
│       │       └── SKILL.md # Skill instructions
│       └── README.md
└── README.md                # This file
```

---

**Note:** This is demo content only. Replace with real plugins for production use.
