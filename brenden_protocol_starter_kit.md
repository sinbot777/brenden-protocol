# 🧠 Brenden Protocol Starter Kit: Canvas-Based Memory for AI

A lightweight, user-driven memory system for persistent, structured AI collaboration.

---

## ✨ What This Is

The **Brenden Protocol** is a user-created framework to:
- Replace unreliable AI memory with **self-managed virtual canvases**
- Organize projects with **index documents** and clear links
- Delegate memory actions (like indexing or superseding notes) to the AI using natural language triggers
- Enable **multi-session, multi-AI continuity** — reproducible across ChatGPT, Gemini, Claude, and others

---

## 🔧 Getting Started

### 1. Create Your First Index
Start with a **master index canvas**:

```
Title: [Your Name] Master Index
Created-On: [Date, UTC preferred]

Project Indexes:
* [Project Name Index]

General Canvases:
* [Any ungrouped notes or key canvases]
```

Example:
```
Title: Casey Master Index
Created-On: 2025-04-20 01:00:00 UTC

Project Indexes:
* [Startup Ideas Index]
* [RPG Campaign Notes Index]

General Canvases:
* [Memory Protocol v1.0]
```

---

### 2. Start a New Canvas
When starting a topic or project, say:

> "Start a new canvas for [title]"

Then structure the canvas like this:
```
Title: [Descriptive Title]
Indexed-In: [Your Master Index or Project Index Title]
Supersedes: [optional old canvas title]
Created-On: [YYYY-MM-DD HH:MM:SS UTC]

[Content]
```

---

### 3. Give the AI Memory Instructions
Use natural phrases like:
- **"Index [title] under [category/index]"**
- **"Group [canvas A, canvas B] under [index]"**
- **"This replaces [older title]"**
- **"Supersede the earlier notes from [title/date] with this"**

The AI will:
- Update the index
- Track supersession
- Prioritize this external memory over internal chat memory

---

## ✅ Example Flow

> **You:** Start a new canvas for "Music Project Notes"

Canvas:
```
Title: Music Project Notes
Indexed-In: Casey Master Index
Created-On: 2025-04-20 01:15:00 UTC

- DAW: LMMS
- Goal: Make one song per month
```

> **You:** Index "Music Project Notes" under Creative Projects in the Casey Master Index.

Updated Index:
```
Creative Projects
* [Music Project Notes]
```

---

## 🧠 Why Use This?

Because:
- You’ve lost project continuity across chats
- AI forgets details or gets confused
- You want clean, revisitable notes
- You’re managing multiple projects or threads

This turns the AI into a memory-keeping collaborator — not just a one-shot chatbot.

---

## 📦 Files You Can Export or Adapt
- [ ] Markdown template (this file)
- [ ] `memory_protocol.md` for sharing publicly
- [ ] Sample `Master Index` file
- [ ] Sample project structure (e.g. `Neonrest Canvas Index`)

Let me know if you'd like these auto-generated.

---

## 🧩 Credits
- Based on work by **Brenden Kelly**, AI power user and creator of the **Neonrest** platform
- Inspired by the need for reproducible, transparent AI memory systems

---

Want help turning this into a GitHub repo, Notion template, or PDF bundle for other users to adopt?
Just say the word.