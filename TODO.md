# 🛠️ Brenden Protocol Improvement Roadmap

A working document tracking feature ideas and implementation phases for improving the Brenden Protocol (canvas-based AI memory management system).

---

## ✅ Phase 1: Immediate Usability Enhancements

### 1. Automated Timestamping
- **Goal:** Auto-fill `Created-On: [UTC timestamp]` in metadata block of new canvases.
- **Status:** Pending implementation
- **Why:** Removes a manual step, ensures consistency across canvases.

### 2. Confirmation Responses
- **Goal:** After each instruction, provide clear feedback like:
  - `✔️ Created canvas '[Canvas Title]'.`
  - `➕ Indexed '[Canvas Title]' under '[Index Title]'.`
  - `🔁 Marked '[Old Canvas Title]' as superseded by '[New Canvas Title]' in '[Index Title]'.`
- **Status:** Pending message style guide
- **Why:** Improves user confidence and transparency of AI behavior.

---

## 🧠 Phase 2: Intelligence and Reliability Boosts

### 3. Implicit Indexing Suggestions
- **Goal:** After new canvas creation, suggest index based on title/content match.
- **Approach:**
  - Compare title against known project/index names.
  - Match on shared keywords, vibes, or prior naming patterns.
  - Example response: `💡 Should I also index 'Vampire Character Sheets' under 'VTM Tools Index'?`
- **Status:** Design phase

### 4. Error Handling for Misfires
- **Goal:** Detect failed instructions or misnamed references.
- **Responses:**
  - `❌ Could not find a canvas titled 'Ghost Plan Alpha'. Did you mean 'Ghost Plans'?`
  - `⚠️ Cannot index until canvas is created. Please start a canvas first.`

---

## ✨ Phase 3: Optional Enhancements / Future-Proofing

### 5. Last Modified Tracking
- **Goal:** Optionally log or display when a canvas was last updated.
- **Potential Use:** For syncing with external systems or user history features.

### 6. Tag Suggestion and Searchability
- **Goal:** Add optional tags or context cues to canvases for smarter retrieval.
- **Example Tags:** `project:neonrest`, `type:index`, `state:superseded`

---

## 📘 Style Guide: Confirmations & Errors (Draft)

### Confirmation Templates:
- `✔️ Created canvas '[Canvas Title]'.`
- `➕ Indexed '[Canvas Title]' under '[Index Title]'.`
- `🔁 Marked '[Old Canvas Title]' as superseded by '[New Canvas Title]' in '[Index Title]'.`

### Error Templates:
- `❌ Could not find a canvas titled '[X]'. Did you mean '[Y]'?`
- `⚠️ Cannot index until a canvas is created.`
- `🚫 '[Instruction]' was not recognized. Please rephrase.`

---

## 📂 Synced With GitHub Repo
- [ ] Add this document as `TODO.md` in: [https://github.com/sinbot777/brenden-protocol](https://github.com/sinbot777/brenden-protocol)
- [ ] Track changes alongside `README.md`
