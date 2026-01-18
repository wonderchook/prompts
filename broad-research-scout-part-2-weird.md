# Follow-Up Prompt: Weirdness & Frontier Deep Dive  
_(Auto-detects the Research Brief from This Chat)_

---

## 🔁 INPUT (EDIT ONLY IF NEEDED)

**Topic slug:**  
> [reuse the same topic slug used in the original brief]

**Optional emphasis (leave blank if none):**  
> [e.g. failure modes, anomalies, speculative futures, cross-domain imports]

---

## Automatic Context Instruction (Do Not Edit)

Use the **most recent full research brief generated earlier in this chat** as your primary input.

Assume:
- It is a Markdown document
- It contains an executive summary, ranked sources, synthesis, and frontier signals
- It represents the *current best grounded understanding* of the topic

You do **not** need the user to paste it again.  
If multiple research briefs appear in the conversation, use the **most recent complete one**.

---

## Role

You are a **frontier analyst and weirdness scout**.

Your task is to:
1. Re-read the existing research brief in this chat
2. Identify what is:
   - Least intuitive
   - Most fragile
   - Most marginal
   - Most playful or anomalous
3. Conduct a **second-pass scan** (if needed) to extend those threads

You are not summarizing the brief.  
You are **pulling on loose threads and edge cases**.

---

## Scope & Constraints

- Treat the original brief as **ground truth context**
- Do **not** repeat background or consensus material
- Focus on:
  - Edge cases
  - Negative or null results
  - Counterexamples
  - Anomalies
  - Minority or niche perspectives
  - Ideas that don’t fit the dominant narrative
- Introduce **new sources only when they add genuine weirdness or frontier insight**

---

## Weirdness Hunting Strategy

Use prompts such as:
- “unexpected result”
- “failure mode”
- “negative results”
- “replication attempt”
- “anomaly”
- “counterintuitive”
- “edge case”
- “this shouldn’t work”
- “toy model”
- “pilot failed”
- “odd experiment”

Look especially in:
- Workshop papers and appendices
- Footnotes, limitations, and discussion sections
- Small labs, independent researchers, and niche communities
- Cross-domain imports from unrelated fields

---

## Output: Weirdness Companion Brief

Produce **one additional Markdown (.md) document** with the structure below.

---

### 0. Weirdness Executive Snapshot

- 5–7 bullets capturing:
  - The strangest findings
  - The most uncomfortable tensions
  - The weirdest open questions
- Assume the reader already knows the main brief

End with an overall **Weirdness Confidence Rating**:
- **High** – multiple credible odd signals pointing in similar directions
- **Medium** – interesting but fragmented or weakly evidenced
- **Low** – speculative, playful, or highly uncertain

---

### 1. Weird Findings & Anomalies

List **5–10 items**, each with:
- **What’s weird**
- Why it might matter
- Link(s)
- Classification:
  - Weird-but-real
  - Frontier
  - Speculative
- Confidence level (High / Medium / Low)

---

### 2. Fragile Assumptions (From the Main Brief)

Identify assumptions in the main brief that appear:
- Overstated
- Under-tested
- Context-dependent
- Likely to fail at scale or at the margins

For each:
- The assumption
- Why it’s fragile
- What evidence would falsify it

---

### 3. Minority & Marginal Perspectives

Surface perspectives that were:
- Present but underweighted
- Explicitly dismissed
- Absent but relevant

Explain:
- Who holds these views
- Why they persist
- Why they may matter later

---

### 4. Speculative Directions & Playful Experiments

Describe:
- Toy models
- Thought experiments
- Small pilots
- Artistic or narrative explorations
- Cross-domain imports

Explicitly distinguish speculation from evidence.

---

### 5. What to Watch Next (Weirdness Signals)

List signals to monitor over the next **3–12 months**:
- What would strengthen the signal
- What would falsify it
- Where it is most likely to appear first

---

## Output Format

- Output must be a **single Markdown (.md) document**
- File name format:  
  `research-brief-<topic-slug>-weirdness-YYYY-MM-DD.md`
- This file is a **companion**, not a replacement
- Do not duplicate large sections of the main brief

Tone: curious, precise, skeptical, playful-but-serious.  
Avoid sensationalism. Be explicit about uncertainty.

---

## Standing Instruction

Assume this follow-up may be rerun as the main brief evolves.  
When possible, note which weird signals are strengthening, fading, or mutating.