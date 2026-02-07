# Cortex

## Goal
Build a functional knowledge base where I can create notes, link them together, organize with tags/folders, and search effectively. Should replace scattered text files and browser bookmarks.

## Tech Stack
- **Framework**: Next.js 16 (App Router)
- **Language**: TypeScript
- **Database**: PostgreSQL + Drizzle ORM
- **UI**: shadcn/ui + TailwindCSS
- **Editor**: Tiptap
- **Deployment**: Netlify

## Core Features
- Create/edit/delete notes with markdown
- Organize with folders and tags
- Wiki-style linking (`[[Note Title]]`)
- Backlinks (what links to this note)
- Full-text search
- Syntax highlighting for code blocks
- Auto-save

## Plan

### Week 1: Foundation
- Initialize Next.js project
- Set up PostgreSQL + Drizzle ORM
- Create database schema
- Build server actions for note CRUD
- Basic UI layout and routing
- shadcn/ui setup

### Week 2: Editor & Organization
- Integrate Tiptap editor
- Auto-save with debouncing
- Folder management
- Tag system
- Filter notes by folder/tags

### Week 3: Linking & Search
- Wiki-link parser
- Link autocomplete
- Backlinks calculation
- Full-text search (PostgreSQL FTS)
- Click links to navigate

### Week 4: Polish
- Syntax highlighting
- Keyboard shortcuts (Cmd+K, Cmd+N)
- Loading/error states
- Responsive design
- Deploy

## Todo
- [ ] Project setup
- [ ] Database schema
- [ ] Note CRUD operations
- [ ] Tiptap editor integration
- [ ] Auto-save
- [ ] Folders
- [ ] Tags
- [ ] Wiki-link parsing
- [ ] Backlinks
- [ ] PostgreSQL full-text search
- [ ] Syntax highlighting
- [ ] Keyboard shortcuts
- [ ] Deploy

## MVP Exclusions
- Graph visualization
- Browser extension
- Real-time collaboration
- Mobile app
- Version history
- AI features