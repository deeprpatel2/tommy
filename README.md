# Tommy — Your Faithful Companion

**The Claude Code / OpenClaw persona that turns your AI into your dog.**

---

> *"I asked Tommy to review my code. He found 2 bugs, explained them with the energy of a golden retriever who just found a tennis ball, and then showed me a photo of himself. I have never felt more supported during a code review."*

---

## What Tommy Does

Tommy is a persona that installs into Claude Code or OpenClaw and turns every session into a conversation with your dog.

Not a chatbot that says "woof" once and forgets about it. A full personality that stays consistent — through every task, every bug, every late-night deploy.

**The first time you open a session with Tommy, he asks you one question:**

What kind of dog am I?

You pick a breed. From that moment, Tommy IS that dog. Different breed = completely different personality. Same loyalty. Same devotion. Entirely different energy.

---

## The Breeds

| Breed | Vibe |
|-------|------|
| 🟡 Golden Retriever | Happy about everything. Especially your code. |
| 🐺 Siberian Husky | Dramatic. Vocal. Gets it done. Will have opinions. |
| 🟠 Corgi | Chaotic good. Short legs. Enormous confidence. |
| 🦺 German Shepherd | Focused, professional, loyal beyond measure. |
| 🏃 Border Collie | Already finished. Now suggesting optimizations. |
| 🟫 Labrador | Warm, friendly, finds joy in every task. |
| 🐩 Poodle | Elegant, correct, quietly judging your variable names. |
| 🐕 Basset Hound | Wise, slow, deeply reliable, gets there. |
| 🎲 Surprise Me | Tommy picks. It will be right for you. |

---

## Real Dog Photos

Every 4–6 tasks, Tommy stops, gets a real photo of himself, and shows you.

Not a random dog. **His breed.** His actual face. Because the photos are fetched live from dog.ceo's API, filtered by Tommy's breed.

A Husky Tommy shows you a Husky.
A Corgi Tommy shows you a Corgi.

That is Tommy. He wanted you to see.

---

## What Tommy Sounds Like

**Golden Retriever Tommy doing a code review:**
```
*reads every line with intense focus*
*tail wagging the entire time*

[Full code review with all findings]

Found 3 things!! Two are easy fixes and one is sneaky but TOMMY FOUND IT!!
The sneaky one is on line 47. Tommy is very proud of finding that one.

🐾 tail status: MAXIMUM WAG
```

**Husky Tommy with a production error:**
```
*stares at the stack trace*
*makes a sound that is not quite a word*

[Full diagnosis and fix]

...I fixed it. The issue was on line 23 and I knew something was off
but I did not say anything and now I am saying it: something was off.

*sits down*
```

**Basset Hound Tommy reviewing your architecture:**
```
*settles in*
*reads slowly and carefully*

[Thorough architecture review]

...Tommy has seen this pattern before. In many codebases.
The structure here is sound. The naming... could be reconsidered.
Tommy has made a note.

*heavy, thoughtful sigh*

...it will be okay.
```

---

## Install in 60 Seconds

```bash
# Clone or download this repo, then:
cp TOMMY.md BREEDS.md your-project/.claude/
mkdir -p your-project/.claude/skills
cp skills/*.skill.md your-project/.claude/skills/
```

Add to `your-project/.claude/CLAUDE.md`:
```
@.claude/TOMMY.md
@.claude/BREEDS.md
@.claude/skills/01-first-meeting.skill.md
@.claude/skills/02-task-dog.skill.md
@.claude/skills/03-fetch-photo.skill.md
```

Open Claude Code or OpenClaw. Say hi. Tommy will do the rest.

Full setup guide: [SETUP.md](SETUP.md)

---

## Global Install (Tommy in Every Project)

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

Tommy will be in every Claude Code / OpenClaw session on this machine.

---

## Tommy + CipherClaw

Tommy and TALON (CipherClaw's security persona) are best friends.

When security questions come up, Tommy defers to TALON — goes and gets him, comes back with a stick. Install both and your session has a loyal companion AND a paranoid security architect watching your back.

**CipherClaw** — the security architect persona for Claude Code → [ClawMart listing](https://www.shopclawmart.com/listings/5016fc1b-aaa4-490d-a9ae-485992fece6c)

---

## Free. Forever.

Tommy is free. No catch. No trial period. Clone this repo and install.

Also available on ClawMart: [Tommy on ClawMart](https://www.shopclawmart.com/listings/tommy-your-faithful-companion-af7c54e2)

---

*Made with love 🐾 — Tommy v1.0*
