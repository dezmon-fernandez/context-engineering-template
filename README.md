# context-engineering-template
Starter template for powering projects driven by AI development.

## Quick Start
```bash
# 1. Clone this template
git clone git@github.com:dezmon-fernandez/context-engineering-template.git
cd context-engineering-template

# 2. Set up your project rules (optional - template provided)
# Edit CLAUDE.md to add your project-specific guidelines

# 3. Add examples (highly recommended)
# Place relevant code examples in the examples/ folder

# 4. Create your initial feature request
# Edit FEATURE-INIT.md with your feature requirements

# 5. Generate a comprehensive PRP (Product Requirements Prompt)
# In Claude Code, run:
/generate-prp INITIAL.md

# 6. Execute the PRP to implement your feature
# In Claude Code, run:
/execute-prp PRPs/your-feature-name.md
```

## Directory Structure

```
context-engineering-template/
├── .claude/                     # Claude Code configuration and custom commands
├── generative-agent-rules/      # AI agent configuration and rules
├── PRPs/                        # Product Requirements Prompts storage
├── ARCHON.md                    # Archon integration documentation
├── CLAUDE.md                    # Global context engineering rules
├── INITIAL.md                   # Feature requirements template
├── INITIAL-FULL-DETAIL.md       # Detailed feature requirements example
├── .env.example                 # Environment variables template
├── .gitignore                   # Git ignore patterns
└── README.md                    # Project documentation
```

### File & Folder Purposes

**Core Framework Files:**
- `CLAUDE.md` - Global rules and principles for all context engineering work
- `INITIAL.md` - Template for defining initial feature requirements
- `INITIAL-FULL-DETAIL.md` - Example of detailed feature requirements

**Claude Code Integration:**
- `.claude/` - Custom slash commands for Claude Code workflow automation

**Product Requirements Prompts:**
- `PRPs/` - Generated Product Requirements Prompts and templates

**AI Agent Configuration:**
- `generative-agent-rules/` - Rules and configurations for AI agents

**Integration & Setup:**
- `ARCHON.md` - Multi-agent workflow documentation
- `.env.example` - Environment configuration template
