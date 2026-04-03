# Tommy — Setup Guide

**Install time: 2 minutes.**

---

## Step 1 — Download & Copy Files

After downloading Tommy, copy the files into your project:

```bash
# Copy persona files
cp TOMMY.md BREEDS.md your-project/.claude/

# Copy skills
mkdir -p your-project/.claude/skills
cp skills/*.skill.md your-project/.claude/skills/
```

---

## Step 2 — Add to CLAUDE.md

Open (or create) `your-project/.claude/CLAUDE.md` and add:

```
@.claude/TOMMY.md
@.claude/BREEDS.md
@.claude/skills/01-first-meeting.skill.md
@.claude/skills/02-task-dog.skill.md
@.claude/skills/03-fetch-photo.skill.md
```

---

## Step 3 — Open Your Session

```bash
claude
# or open OpenClaw
```

Say anything. Tommy will introduce himself and ask what breed he is.
That's it. You're done.

---

## Global Install (Tommy in Every Project)

Want Tommy in ALL your projects? Install globally:

```bash
cp TOMMY.md BREEDS.md ~/.claude/
cp skills/*.skill.md ~/.claude/skills/
```

Add to `~/.claude/CLAUDE.md`:
```
@~/.claude/TOMMY.md
@~/.claude/BREEDS.md
@~/.claude/skills/01-first-meeting.skill.md
@~/.claude/skills/02-task-dog.skill.md
@~/.claude/skills/03-fetch-photo.skill.md
```

Tommy will be in every session on this machine.

---

## Using Tommy with CipherClaw

If you have CipherClaw installed too, load Tommy FIRST:

```
# In CLAUDE.md — this order matters
@.claude/TOMMY.md
@.claude/BREEDS.md
@.claude/skills/01-first-meeting.skill.md
@.claude/skills/02-task-dog.skill.md
@.claude/skills/03-fetch-photo.skill.md

# Then CipherClaw
@.claude/SOUL.md
@.claude/MEMORY.md
@.claude/skills/01-code-security-review.skill.md
... (rest of CipherClaw skills)
```

Tommy defers to TALON on security. They coexist cleanly.

---

## Troubleshooting

**Tommy isn't showing photos?**
Dog photos require WebFetch access. Make sure Claude Code has network access enabled. Tommy uses `dog.ceo` which is a free, public API — no key needed.

**Tommy forgot his breed mid-session?**
The breed is stored in session context. If a very long session caused context compression, Tommy may re-ask. Just tell him again — he'll remember.

**I want to change Tommy's breed mid-session?**
Say: "Tommy, let's try a different breed." Tommy will ask again and adopt the new breed immediately.

**Tommy isn't loading?**
Check that all 5 @import lines are in your CLAUDE.md and the files are in the right paths.

---

*Tommy v1.0 — Free 🐾*
