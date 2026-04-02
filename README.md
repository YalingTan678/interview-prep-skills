# Interview Prep Skills

Systematic interview preparation skills for university students (undergrad, master's, PhD). Uses product thinking frameworks (JTBD, Value Proposition Design, Continuous Discovery, Playing to Win) applied to interview prep.

![Skills Overview](assets/skills-overview.png)

![Workflows Overview](assets/workflows-overview.png)

## Core Skills

| Skill | What it does | Framework |
|---|---|---|
| **jd-decoder** | Analyze a job description to reveal the employer's real needs | Jobs to Be Done (JTBD) |
| **role-investigator** | Systematic research: official sources → LinkedIn → community → interviewer profiling | Continuous Discovery |
| **value-proposition** | Map your experiences to employer needs, build stories, create positioning statement | Value Proposition Design |
| **mock-interview** | Generate targeted questions + interactive mock practice with feedback | — |

## Exploration & Materials

| Skill | What it does | Framework |
|---|---|---|
| **career-explorer** | Help students who don't know what they want figure out their direction | Playing to Win (Where to Play) |
| **resume-tailor** | Strategically align a resume/CV to a specific job description | — |
| **thank-you-note** | Write effective post-interview thank-you emails | — |

## Position-Specific Deep Dives

| Skill | For | Unique elements |
|---|---|---|
| **ta-prep** | Teaching Assistant positions | Teaching demo prep, teaching philosophy, pedagogy questions |
| **ra-prep** | Research Assistant positions | PI research alignment, methodology discussion, tools inventory |
| **ga-prep** | Graduate Assistantships (student services) | Mission alignment, scenario-based questions, DEI competency, career development theories |
| **internship-prep** | Industry internships | Multi-stage process, "Why this company?", STAR method, potential-over-experience framing |

## Commands (Chained Workflows)

| Command | What it does |
|---|---|
| **/full-prep** | Complete systematic preparation: jd-decoder → role-investigator → value-proposition → mock-interview |
| **/quick-prep** | Emergency mode for interviews tomorrow: rapid JD scan → 3 stories → 5 questions → checklist |
| **/explore** | Career exploration: self-assessment → position mapping → next steps |

## Getting Started

### Step 1: Install Claude Code

If you don't have it yet, install [Claude Code](https://docs.anthropic.com/en/docs/claude-code) (Anthropic's CLI for Claude):

```bash
npm install -g @anthropic-ai/claude-code
```

### Step 2: Clone this repo

```bash
git clone https://github.com/YalingTan678/interview-prep-skills.git
```

### Step 3: Add skills to Claude Code

Open Claude Code and point it to the skills:

```bash
cd interview-prep-skills
claude
```

Then tell Claude what you need. For example:

> "I have an interview for a TA position in the CS department next week. Help me prepare."

> "I just found this job posting for a Graduate Assistantship at the career center. Can you decode the JD for me?"

> "I don't know what kind of jobs I should apply for. Help me explore."

Claude will automatically use the relevant skills to guide you through a structured preparation process.

### Quick Examples

| You say | What happens |
|---|---|
| "I have an interview next Wednesday for a GA position" | Full systematic prep: JD analysis → research → value proposition → mock practice |
| "My interview is tomorrow, help!" | Emergency mode: 3 key stories, 5 likely questions, day-of checklist |
| "I don't know what I want to do" | Career exploration: self-assessment → position mapping → next steps |
| "Can you look at this job description?" | JD Decoder: reveals hidden requirements and employer's real needs |
| "Help me tailor my resume for this posting" | Resume Tailor: keyword mapping, bullet surgery, gap analysis |
| "Let's do a mock interview" | Targeted questions based on your JD analysis + real-time feedback |

### Typical Journey

```
Still exploring?          →  /explore
Found a posting?          →  jd-decoder → role-investigator → resume-tailor
Got an interview?         →  /full-prep (+ ta-prep, ra-prep, ga-prep, or internship-prep)
Interview is tomorrow?    →  /quick-prep
Interview done?           →  thank-you-note
```

## Design philosophy

These skills teach **methods, not answers**. Instead of giving students generic tips they can find anywhere, we teach frameworks they can reuse for every future interview:

1. **JTBD**: Understand what the employer actually needs (not what the JD says)
2. **Continuous Discovery**: Research systematically — official sources, LinkedIn, community platforms, informational interviews
3. **Value Proposition Design**: Match your specific experiences to their specific needs with concrete stories
4. **Playing to Win**: Figure out where to focus your energy before competing
5. **Targeted practice**: Questions derived from analysis, not a generic question bank

## Architecture

```
interview-prep-skills/
├── career-explorer/SKILL.md      ← Career direction exploration (Where to Play)
├── jd-decoder/SKILL.md           ← Decode job descriptions (JTBD)
├── role-investigator/SKILL.md    ← Systematic role research (Continuous Discovery)
├── resume-tailor/SKILL.md        ← Strategic resume alignment
├── value-proposition/SKILL.md    ← Experience-to-needs matching
├── mock-interview/SKILL.md       ← Mock interview + feedback
├── thank-you-note/SKILL.md       ← Post-interview follow-up
├── ta-prep/SKILL.md              ← Teaching Assistant specialization
├── ra-prep/SKILL.md              ← Research Assistant specialization
├── ga-prep/SKILL.md              ← Graduate Assistantship (all campus offices)
├── internship-prep/SKILL.md      ← Industry internship specialization
└── commands/
    ├── full-prep.md              ← Complete preparation workflow
    ├── quick-prep.md             ← Emergency prep mode
    └── explore.md                ← Career exploration workflow
```

## Acknowledgments

The architecture and framework selection for this project were inspired by [PM Skills Marketplace](https://github.com/phuryn/pm-skills) by Paweł Huryn. Their approach of applying product thinking frameworks (JTBD, Value Proposition Design, Continuous Discovery Habits, Playing to Win) through structured, interactive AI skills directly influenced how we designed this interview prep ecosystem. We adapted these product strategy frameworks to the domain of interview preparation for university students.

The frameworks themselves are based on the work of:
- Anthony W. Ulwick — *Jobs to Be Done*
- Strategyzer — *Value Proposition Design*
- Teresa Torres — *Continuous Discovery Habits*
- Roger L. Martin — *Playing to Win*
