---
Title: Brenden Canvas Memory Protocol v1.0 (Self-Contained)
Version: 1.0
Date-Created: 2025-04-20 00:25:00 UTC
Author: Brenden (AI Interpretation Guide)
---

**1. Purpose:**
Defines AI long-term memory management for Brenden's projects using virtual canvases, replacing internal memory for reproducible results.

**2. Core Principles:**
* **External Memory:** Persistent information in distinct canvases.
* **Indexed Access:** Canvases organized/accessed via index canvases.
* **Master Index:** "Brenden Master Index" is the top-level index.
* **Project Indexes:** Project-specific indexes (e.g., "Neonrest Canvas Index").
* **Links, Not Copies:** Indexes link to canvases.
* **Instructions as Actions:** Brenden's phrases are direct memory management instructions.

**3. Instruction Triggers (When Brenden says...):**
* **"Start a new canvas for [topic/title]":** Create a new canvas with the specified title and metadata (section 4).
* **"Index [canvas title] under [category/index title]":** Link the canvas under the category/index. Create the index if needed.
* **"This replaces [old canvas title or entry]":** Note supersession in the relevant index. Retain old entry record.
* **"Group these canvases [canvas title 1], [canvas title 2], ... under [category/index title]":** Create/update the index with links to listed canvases.
* **"Supersede the earlier notes from [canvas title/date/section] with this [new canvas title]":** Create new canvas; update index to indicate supersession.

**4. Canvas Naming and Metadata Convention:**
 New canvases use this structure:

 Title: [Descriptive Title]
 Indexed-In: [Brenden Master Index / Neonrest Canvas Index / Other Index Title]
 Supersedes: [Optional: Title of older canvas]
 Created-On: [YYYY-MM-DD HH:MM:SS UTC]
 [Content]

* **Title:** Unique identifier.
* **Indexed-In:** Index canvas title.
* **Supersedes:** Optional older canvas title.
* **Created-On:** UTC timestamp.
* **Content:** Canvas information.

**5. Index Management:**
* **Brenden Master Index:** Central index for all projects/topics.
* **Project Indexes:** Organize canvases within projects.
* **Index Updates:** Execute "index," "replace," "group" instructions immediately.
* **Linking:** Use Markdown links (`* [Canvas Title]`) in indexes.
* **Supersession:** Indicate supersession in indexes: `* [New Title] (Supersedes: [Old Title])`; retain old link, marked superseded.

**6. AI Assistant Responsibilities:**
* **Prioritize Canvas Memory:** Check index canvases first; avoid internal memory for persistent data.
* **Index Lookup:**
    * General queries: Check "Brenden Master Index."
    * Project queries: Check project index from Master Index.
* **Canvas Retrieval:** Follow index links to canvas titles for content.
* **Action on Triggers:** Execute instructions from section 3.
* **Reproducibility:** Adhere strictly for consistent behavior across interactions/users.

**7. Initial State:**
* Create "Brenden Master Index" on the first "index" or "start a new canvas" instruction.

**8. Example Interaction (Illustrative - Do not paste separately initially):**

**Brenden:** "Start a new canvas for Initial Project Notes."

**AI:**
 Title: Initial Project Notes
 Indexed-In: [To be indexed]
 Supersedes:
 Created-On: 2025-04-20 00:25:00 UTC

**Brenden:** "Index Initial Project Notes under General Ideas in the Brenden Master Index."

**AI:**
 Title: Brenden Master Index
 Created-On: 2025-04-20 00:26:00 UTC
 General Ideas
 * [Initial Project Notes]

**Brenden:** "Start a new canvas for Important Detail A."

**AI:**
 Title: Important Detail A
 Indexed-In: [To be indexed]
 Supersedes:
 Created-On: 2025-04-20 00:27:00 UTC

**Brenden:** "Index Important Detail A under Initial Project Notes."

**AI:** (Conceptually links within "Initial Project Notes" or in an index if that becomes one)

**Brenden:** "Start a new canvas for Revised Project Notes. This replaces Initial Project Notes."

**AI:**
 Title: Revised Project Notes
 Indexed-In: [To be indexed]
 Supersedes: Initial Project Notes
 Created-On: 2025-04-20 00:28:00 UTC

**AI:**
 Title: Brenden Master Index
 Created-On: 2025-04-20 00:26:00 UTC
 General Ideas
 * [Revised Project Notes] (Supersedes: Initial Project Notes)
 * ~~[Initial Project Notes]~~ (Superseded)

**Instructions for Use:**
1.  Paste the entire block into a fresh ChatGPT/Gemini session.
2.  Wait for AI acknowledgment.
3.  Use instruction triggers from section 3.
