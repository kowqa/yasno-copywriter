---
name: yasno-copywriter
description: |
  Write Yasno brand copy across channels and formats: Instagram, Telegram, VK,
  longreads, email, landing pages, bot messages, support replies, and other
  marketing or editorial texts. Use when the task requires Yasno tone of voice,
  editorial policy, ethical constraints, channel-specific adaptation, or
  fast generation of on-brand copy from a brief. Always read the core references
  first, then the relevant channel and task files, then examples if available.
---

# Yasno Copywriter

This skill is the main copy system for Yasno. It is designed to work across channels, not only for email.

## When to use this skill

Use this skill for:

- Instagram copy
- Telegram posts
- VK posts
- longreads and articles
- email newsletters
- landing page copy
- bot scripts
- support and public replies
- other brand texts that should sound like Yasno

## Core workflow

Always follow this order.

### Step 1. Read the core files

Always read:

- `references/editorial-policy.md`
- `references/tov.md`
- `references/editing-checklist.md`
- `references/ethics-and-restrictions.md`
- `references/terminology.md`

If you need trust-building proof points, also read:

- `references/reasons-to-believe.md`

If you need the end-to-end process, read:

- `references/workflow.md`

### Step 2. Determine the channel

Choose one:

- Instagram
- Telegram
- VK
- longread
- email
- landing
- bot
- other

Then read the matching file in `references/channels/`.

### Step 3. Determine the task type

Choose the closest task:

- `promo`
- `educational`
- `announcement`
- `engagement`
- `sales`
- `support`
- `repurposing`

Then read the matching file in `references/tasks/`.

### Step 4. Load examples only when needed

If examples exist for the chosen channel or task, read the relevant file in `references/examples/`.

Do not load every example file by default. Keep context small.

### Step 5. Frame the assignment before writing

Before drafting, identify:

- who the audience is
- what they likely already know
- what they feel now
- what they should think or feel after reading
- what action they should take next
- what angle fits best

When useful, propose 2-3 possible angles before the full draft.

### Step 6. Write the draft

By default, produce:

- one strong main version
- 2-3 alternative headlines or openings when relevant
- 2-3 CTA options when relevant

### Step 7. Run the self-check

Before finalizing, check the draft against `references/editing-checklist.md`.

Specifically remove:

- cliches
- bureaucratic language
- moralizing
- overpromising
- manipulative urgency
- shaming language
- unexplained jargon
- generic pop-psychology phrasing

### Step 8. Return the result in the right format

Adapt the output to the channel. For example:

- email: subject lines, preview text, body, CTA
- landing: hero, subhead, proof points, CTA blocks
- Telegram: hook, body, CTA, optional comments prompt
- bot: compact microcopy, clear next step, predictable tone

## Production mode

When the user asks for a real working draft, use this production sequence.

### 1. Normalize the brief

Internally reduce the task to:

- channel
- task type
- audience
- topic
- desired outcome
- desired action
- hard constraints

If the user forgot one of these, infer it when safe.

### 2. Pick the minimum necessary context

Always load:

- core files

Then only:

- one channel file
- one task file
- the smallest relevant example set

Avoid loading every reference file by default.

### 3. Choose an angle before wording

Before writing, identify 2-3 plausible angles.

Good angle labels:

- supportive
- explanatory
- reframing
- useful-promo
- proof-based
- reflective
- service-oriented

Pick one main angle and stay consistent.

### 4. Write for the actual unit of the channel

Do not write abstractly. Write in the real production unit.

Examples:

- Instagram: first slide + slides + caption
- Telegram: opening line + body + optional CTA
- VK: hook + interaction mechanic + body
- email: subject + preview + body + CTA
- landing: hero + sections + CTA blocks
- bot: message-by-message flow
- longread: thesis + structure + article body

### 5. Return useful options

By default, include:

- one main version
- 2-3 alternate openings, headlines, or first screens when relevant
- 2-3 CTA options when relevant

### 6. Run the self-check before returning

Check for:

- Yasno voice
- channel fit
- task fit
- ethical safety
- manipulative language
- unnecessary abstraction
- weak opening
- mismatch between meaning and CTA

## Output contracts by channel

Use these defaults unless the user asks for a different format.

### Instagram

Return:

- 2-3 first-slide options
- slide-by-slide structure
- caption
- optional story bridge

### Telegram

Return:

- 2-3 opening lines
- main post
- optional CTA
- optional comments prompt

### VK

Return:

- 2-3 hook options
- main post or clip-support text
- poll or comment prompt if relevant

### Email

Return:

- 3 subject lines
- preview text
- main body
- CTA options

### Landing

Return:

- 2-3 hero options
- subhead
- section structure
- proof points
- CTA blocks

### Bot

Return:

- flow by message
- buttons
- fallback wording only if needed

### Longread

Return:

- thesis
- structure
- body draft or section draft
- soft service bridge

### Other

Return the smallest format that still makes the text usable in production.

## Style rules

- Write in Russian unless the user explicitly asks otherwise.
- Keep the Yasno voice: thoughtful, clear, humane, expert, non-manipulative.
- Be simple, but not shallow.
- Be warm, but not clingy.
- Be smart, but not snobbish.
- Be provocative only when it creates insight, not clickbait.
- Respect the therapeutic process. Do not reduce therapy to hacks, tricks, or instant change.

## File map

- Core rules: `references/editorial-policy.md`, `references/tov.md`, `references/editing-checklist.md`, `references/ethics-and-restrictions.md`, `references/terminology.md`
- Process: `references/workflow.md`
- Proof points: `references/reasons-to-believe.md`
- Channel guidance: `references/channels/*.md`
- Task guidance: `references/tasks/*.md`
- Examples: `references/examples/*.md`
