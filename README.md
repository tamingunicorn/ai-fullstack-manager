# AI Fullstack Manager

Cursor rules for seamless full-stack development with Next.js + FastAPI. Enables AI to intelligently switch between frontend and backend contexts without confusion.

## Quick Start

1. Copy `ai-fullstack-manager-latest.mdc` to your project's `.cursor/rules/` directory
2. Set the rule to "always" in Cursor settings (crucial for context switching)
3. Structure your project with `frontend/` and `backend/` directories
4. Let Cursor automatically detect and switch contexts based on your working directory

## What It Does

- **Context-Aware Development**: Automatically switches between frontend/backend modes
- **Unified Memory System**: Maintains project state across both stacks
- **Auto-Testing**: Validates changes in real-time for both FE and BE
- **Integration Patterns**: Manages API contracts and shared resources

## Pros

✅ **No More Confusion**: AI stays focused on correct stack  
✅ **Seamless Integration**: Handles FE-BE communication patterns  
✅ **Auto-Validation**: Tests both sides after changes  
✅ **Unified Context**: Single source of truth for full-stack projects

## Cons

❌ **Setup Required**: Needs specific folder structure  
❌ **NextJS + FastAPI**: Currently optimized for this stack  
❌ **Learning Curve**: Requires understanding of context system

## Customization

The `.mdc` file can be modified for other frameworks:

- Replace NextJS patterns with React, Vue, etc.
- Swap FastAPI for Django, Express, etc.
- Adjust testing protocols for your stack

## Framework Support

**Current**: Next.js + FastAPI  
**Adaptable to**: Any frontend + backend combination

## Inspiration

Highly inspired by [@vanzan01/cursor-memory-bank](https://github.com/vanzan01/cursor-memory-bank) - an excellent framework for structured AI development workflows.

## Structure

```
your-project/
├── .cursor/rules/ai-fullstack-manager-latest.mdc
├── frontend/          # Next.js app
├── backend/           # FastAPI app
├── shared/            # Common types/utils
└── .context/          # AI memory system
```

That's it. Start coding and let the AI handle the context switching.
