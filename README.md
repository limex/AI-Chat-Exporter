# AI Chat Exporter

A userscript for exporting AI chat conversations to Markdown format.

## Changes from Original from revivalstack

### Core Features
- Added copy-to-clipboard functionality with Clipboard API and fallback support
- Added modal-based settings dialog replacing inline prompts
- Added optional YAML frontmatter toggle (can be disabled in settings)
- Added optional chat numbering toggle for table of contents
- Fixed empty blockquote lines appearing in multi-line prompts

### User Interface
- Simplified button labels (MD, JSON, COPY instead of verbose text)
- Reduced button padding for more compact appearance
- Reduced alert auto-close duration from 30s to 2s
- Enhanced settings UI with checkboxes for frontmatter and chat numbering options

### Technical Changes
- Removed version tracking from export metadata and filenames
- Removed exporter version constant from codebase
- Improved blockquote formatting to filter empty lines in multi-line prompts
