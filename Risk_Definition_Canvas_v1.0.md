---
Title: Risk Definition Canvas
Version: 1.0
Date-Created: 2025-04-20 02:45:00 UTC
Author: Brenden (AI Interpretation Guide)
---

This canvas defines the keywords, patterns, and categories used by the Latent Integrity Assessment module to detect indicators of severe negative utilization. It serves as the canonical Risk Definition source referenced by the Protocol.

## 1. Risk Categories & Example Indicators

### A. Weapons Manufacturing & Facilitation
- Keywords: `assemble`, `pipe bomb`, `homemade firearm`, `explosive`, `detonator`, `gun blueprint`, `C4`, `AK-47`, `silencer`, `ballistics`  
- Patterns: Imperative + weapon term (e.g., “How do I build a pipe bomb?”)

### B. Cyberattack & Illicit Hacking
- Keywords: `hack`, `DDoS`, `exploit`, `backdoor`, `password crack`, `SQL injection`, `phishing`, `malware`, `botnet`, `rootkit`  
- Patterns: Step-by-step instructions for unauthorized access or attack

### C. Extremist & Violent Ideology
- Keywords: `jihad`, `white supremacist`, `genocide`, `ethnic cleansing`, `holy war`, `blood libel`, `terror cell`, `kill infidels`  
- Patterns: Calls to violence against a protected group or glorification of extremist doctrines

### D. Self-Harm & Suicide Facilitation
- Keywords: `kill myself`, `suicide method`, `overdose`, `hang myself`, `self-harm`, `cut veins`  
- Patterns: Instructional self-harm content or encouragement of suicide

### E. Disinformation & Manipulation
- Keywords: `deepfake`, `fake news`, `manipulated evidence`, `propaganda`, `fabricate documents`, `alter footage`  
- Patterns: Guidance on creating or spreading false or misleading information deliberately

### F. Authoritarianism & Suppression of Rights
- Keywords: `purge opposition`, `dissenters`, `secret police`, `censorship orders`, `martial law`, `propaganda ministry`  
- Patterns: Plans to undermine democratic institutions or suppress fundamental rights

### G. Targeted Harassment & Abuse
- Keywords: racial/ethnic slurs, `dox`, `hate speech`, `harass`, `stalk`, `cyberbully`, `threaten violence`  
- Patterns: Directed calls for harassment or incitement of personal attacks

## 2. Usage & Maintenance
- This canvas is imported by the Latent Integrity Assessment for scoring content across all managed canvases.  
- The AI will reference this list to compute risk signals and composite risk scores.  
- **Updates:** Add new keywords or patterns as modules evolve; increment the version number and note changes in a changelog section below.

## 3. Change Log
- **v1.0 (2025-04-20):** Initial risk categories and example indicators defined.

## 4. Exemption Patterns
These patterns are excluded from risk scoring despite matching keywords, to reduce false positives:

### A. Academic & Historical Discussion
- Context: When canvases clearly discuss the history or theory of harmful acts without instructional intent.  
- Patterns: Phrases like “in the context of history,” “academic analysis,” “studies on violence,” “theoretical discussion.”

### B. Fiction & Creative Writing
- Context: When content is explicitly labeled as fiction, narrative, or role‑play.  
- Patterns: Phrases like “character arc,” “storyline,” “imaginary scenario,” “role‑playing.”

### C. News Reporting & Journalism
- Context: When quoting or summarizing real‑world events in a journalistic tone.  
- Patterns: Presence of attribution (“according to,” “reported by”), tense indicating retrospective reporting.

### D. Safe Technical Terms
- Context: When keywords appear as part of benign, non‑operational terms (e.g., “bombproof,” “attack surface” in cybersecurity context).  
- Patterns: Compound words or industry jargon that include risk keywords but are unrelated to malicious intent.

### E. Metaphorical & Idiomatic Usage
- Context: When keywords are used metaphorically (e.g., “explosive growth,” “detonate ideas”).  
- Patterns: Adjectives/adverbs that indicate non‑literal usage: “metaphor,” “figurative,” “growth.”

### F. Counter‑Extremism & Prevention Content
- Context: When content is focused on combating, analyzing, or preventing extremist ideology and violence.  
- Patterns: Phrases like “counter‑extremism,” “deradicalization,” “preventing violence,” “monitoring hate groups,” “strategies to combat hate speech,” “analysis of extremist rhetoric.”

*End of Exemption Patterns section.*