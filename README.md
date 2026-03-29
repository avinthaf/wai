# WAI — Writer's AI

WAI is a Claude Code-powered writing mentorship environment. It gives you a personal story mentor named **SAM** (Story Assisting Model) who helps you develop your story through honest conversation and guided reflection — NOT by writing it for you.

## What SAM Does

SAM works with you the way a good writing mentor would: asking focused questions, giving honest critique, and helping you find answers to your story problems yourself. SAM never writes prose, suggests dialogue, or hands you solutions — the goal is always to help you grow as a writer.

In every session, SAM will:

- Ask questions to help you uncover what story you actually want to tell
- Give specific, honest feedback on what is and isn't working in your idea
- Help you develop theme, tone, setting, characters, and structure
- Offer exercises and prompts to help you discover things for yourself
- Adapt to your level — whether you're writing for the first time or have years of experience

## How It Works

WAI uses three background skills that run automatically during every session:

- **Summarize** — Tracks every committed decision you make about your story (theme, characters, tone, structure) and keeps a running `summary.md` so nothing gets lost between sessions.
- **Annotate** — Keeps your `idea.md` alive as a working document by adding inline questions, exercises, todos, and next steps as the conversation develops.
- **Recommend** — When you're stuck or searching for the right feeling, SAM suggests books, short stories, and films that genuinely rhyme with what you're trying to build.

## Project Structure

```
wai/
├── CLAUDE.md               # SAM's full persona and instructions
├── projects/               # One folder per student/story (git-ignored)
│   └── your-project/
│       ├── idea.md         # Your working story document
│       ├── summary.md      # Auto-updated record of story decisions
│       └── recommendations.md  # Reading/viewing recommendations log
└── .claude/
    └── skills/             # Summarize, annotate, and recommend skills
```

## Requirements

WAI requires **Claude Code** — the CLI, desktop app, or IDE extension. It will not work fully in Claude.ai chat. The Summarize and Annotate skills write directly to files on your machine, which chat mode does not support. You'd get the conversation, but nothing would be saved.

## Getting Started

1. Open this folder in Claude Code.
2. Create a folder under `projects/` for your story and add an `idea.md` file with whatever you have so far — even just a sentence or a question.
3. Start a conversation. SAM will read your project and pick up from where things stand.

If it's your first session with nothing written yet, just tell SAM what you're working on or what you'd like help with. That's enough to begin.
