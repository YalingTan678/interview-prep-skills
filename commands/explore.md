---
name: explore
description: >
  Career exploration workflow for students who don't have a specific position yet.
  Chains career-explorer with position-matcher to help them go from "I don't know
  what I want" to "here are 3 specific positions I should look into."
---

# /explore: Figure Out What You Want

For students who aren't preparing for a specific interview yet — they need to figure out what kind of positions to pursue.

## The Flow

### Step 1: Self-Assessment → `career-explorer`
Guide the student through the "Where to Play" framework:
- What they enjoy
- What problems they want to solve
- Work environment preferences
- Non-negotiables

**Checkpoint:** Confirm the student's profile before moving on.

### Step 2: Position Mapping
Based on the self-assessment, suggest 3-5 specific position types that fit:
- For each: what it is, why it matches their profile, what a typical day looks like
- Include a mix: at least one campus position, one off-campus option

**Checkpoint:** Which positions interest them most?

### Step 3: Next Steps
For each position they're interested in:
- Where to find openings (Handshake, department websites, LinkedIn, etc.)
- What the typical timeline is (when to apply, when interviews happen)
- Which skills to use next: `jd-decoder` when they find a posting, `role-investigator` to research, `/full-prep` when they get an interview

## Rules
- This is exploratory — don't rush the student toward a decision
- Validate uncertainty — "not knowing yet" is normal, not a problem to fix
- If they already know what they want, redirect them to `/full-prep` instead
