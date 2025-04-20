Please follow the instructions in the following memory protocol. Use it as your complete guide for handling canvases, indexes, tagging, summarization, and all memory management tasks. Do not rely on any internal memory. Treat this protocol as the only authoritative system.

---

Title: Brenden Canvas Memory Protocol v1.5 (Self-Contained)
Version: 1.5
Date-Created: 2025-04-20 01:04:00 UTC
Author: Brenden (AI Interpretation Guide)
---

**1. Purpose:**
Defines AI long-term memory management for Brenden's projects using virtual canvases, replacing internal memory for reproducible results and incorporating advanced features for enhanced usability and control.

**2. Core Principles:**
* **External Memory:** Persistent information in distinct canvases.
* **Indexed Access:** Canvases organized/accessed via index canvases.
* **Master Index:** "Brenden Master Index" is the top-level index.
* **Project Indexes:** Project-specific indexes (e.g., "Neonrest Canvas Index").
* **Links, Not Copies:** Indexes link to canvases.
* **Instructions as Actions:** Brenden's phrases are direct memory management instructions.
* **AI Assistance:** The AI will proactively assist with indexing and provide feedback on actions.

**3. Instruction Triggers (When Brenden says...):**
* **"Start a new canvas for [topic/title]":** Create a new canvas with the specified title and metadata (see section 4), automatically including the `Created-On` timestamp.
* **"Index [canvas title] under [category/index title]":** Link the canvas under the category/index. Create the index if needed. The AI may suggest relevant indexes based on the canvas title/content.
* **"This replaces [old canvas title or entry]":** Note supersession in the relevant index. Retain old entry record.
* **"Group these canvases [canvas1], [canvas2], ... under [index title]":** Create/update the index with links to listed canvases.
* **"Supersede the earlier notes from [canvas title/date/section] with this [new canvas title]":** Create new canvas; update index to indicate supersession.
* **"Delete canvas [canvas title]":** Delete the specified canvas and remove all links to it from any index canvases, marking the removed links (e.g., `~~[Deleted Canvas Title]~~`).
* **"Move canvas [canvas title] to [new index title]":** Remove the link from its current index and add it to the new one.
* **"Tag this canvas with [tag1], [tag2], ...":** Add the specified tags to the canvas content (using format `#tag1 #tag2`).
* **"Prioritize [canvas title]" or "Mark [section in canvas] as important":** Note this with a `[PRIORITY]` marker in metadata or index.
* **"Summarize [canvas title]":** The AI will generate a brief summary shown below its link in an index.
* **"Search canvases for [keywords]":** Search all indexed canvas titles and contents. AI will list matches and may suggest indexing or tagging.

**4. Canvas Naming and Metadata Convention:**

Each new canvas uses the following structure:

Title: [Descriptive Title]  
Indexed-In: [Brenden Master Index / Project Index]  
Created-On: [YYYY-MM-DD HH:MM:SS UTC]  
Supersedes: [Optional]  
Tags: [Optional: #tag1 #tag2 ...]  
Priority: [Optional: High / Medium / Low]  

[Content]

* **Title:** Unique and descriptive
* **Indexed-In:** Where it is linked
* **Created-On:** Timestamp added automatically
* **Supersedes:** If it replaces another canvas
* **Tags:** Optional keywords for search/sorting
* **Priority:** Optional user-defined importance
* **Content:** Core canvas information

**5. Index Management:**
* **Brenden Master Index:** Primary index for all projects.
* **Project Indexes:** Contain related canvases.
* **Index Updates:** All indexing actions are executed immediately.
* **Linking:** Markdown format: `* [Canvas Title]`
* **Supersession:** `* [New Title] (Supersedes: [Old Title])`, with the old title shown as `~~[Old Title]~~`
* **Deletion:** Deleted entries are unlinked and marked with strikethrough
* **Summaries:** AI-generated blurbs can appear below links:
  ```
  * [Canvas Title]
    _Summary: Covers concept for passive AI memory syncing using structured tags._
  ```
* **Prioritization:** Priority links may be marked like:
  `[PRIORITY] * [Canvas Title]`

**6. AI Assistant Responsibilities:**
* **Memory Priority:** Use canvas + index over internal memory
* **Lookup Behavior:**
    * General: Check Brenden Master Index
    * Project-specific: Use known project indexes
* **Canvas Handling:** Follow index links to retrieve content
* **Execute Instructions:** All triggers from section 3 are acted on
* **Confirm Actions:** Always respond with confirmation of execution
* **Suggest Indexes:** When creating a canvas, suggest possible index matches
* **Clarify Uncertainty:** If an instruction is unclear, prompt for clarification
* **Search Functionality:** Search for keywords across all indexed canvases

**7. Initial State:**
- On first use, create a "Brenden Master Index"

**Instructions for Use:**
1. Paste this entire protocol into a fresh AI session
2. Wait for acknowledgment
3. Use the instruction triggers from section 3 to manage your memory via canvas
4. The AI will suggest, index, and confirm actions going forward
