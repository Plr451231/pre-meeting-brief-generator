# Pre-Meeting Brief Generator

An AI sales tool that produces operator-quality pre-meeting briefs for enterprise account executives — built by a sales leader who got tired of reps walking into discovery calls with a Google search and a LinkedIn skim.

---

## Why this exists

The reps who use AI well are pulling ahead of the ones who don't, and the gap shows up in pipeline within a quarter. Everyone says this. Nobody hands their team a working tool.

This is one. Built in an afternoon. Free.

You give it a target company and a meeting attendee. It returns a structured one-page brief: recent company news, who you're meeting and what they own, likely budget owner, vendor landscape, NEPQ-style conversation hooks, risk flags, and the one thing to remember walking in.

Designed for AEs preparing for discovery, expansion, or renewal calls. Also works for interview prep, partnership meetings, and donor calls if you're in nonprofit fundraising.

---

## What you get

Every brief follows the same structure:

1. **What's happening at the company** — last 90 days
2. **Who you're meeting** — title, tenure, what they own, recent public signals
3. **Likely budget owner & buying committee** — with procurement complexity flag
4. **Vendor landscape** — incumbents, replacement risk flag
5. **Conversation hooks** — problem-aware, NEPQ-style, not pitch
6. **Risk flags** — things that could kill the deal early
7. **The one thing to remember** — single sentence the rep holds in their head

---

## How to use it

1. Go to [claude.ai](https://claude.ai) and create a free account if you don't have one.
2. Create a new Project. Call it **Pre-Meeting Brief Generator**.
3. Open `prompt.md` from this repo, copy the entire contents, and paste into the Project's **Custom Instructions** field.
4. In the chat, type:
   `Build me a brief on [Company Name]. I'm meeting [Name, Title] next week.`
5. Answer the two clarifying questions the tool asks (it won't invent missing info — that's a feature).
6. Get your brief.

---

## Example output

Real output in `/examples`:

- `anthropic-kate-jensen.md` — interview prep brief for an enterprise AE candidate at Anthropic

More examples coming as I run the tool against my own target list.

---

## Design choices worth noting

- **No hallucination by design.** When the tool doesn't know something, it says "Unknown — verify before call." Hiring managers care about this.
- **NEPQ-flavored hooks**, not generic discovery questions. Problem-aware open, status-quo challenge, consequence.
- **One page, scannable in 90 seconds.** A brief a rep won't read is a brief that doesn't exist.
- **Source citations inline.** Earnings calls, LinkedIn posts, press releases. So the rep can verify before they use it.

---

## About the author

Parker Robinson — 20 years in B2B and financial sales. $20M book built from cold calls at Morgan Stanley (Blue Chip Club, top 5%). Ran a 12-person sales team, $50M+ in new sales at peak. Deployed AI prospecting tooling in a production sales workflow before "AI for sales" was on a hiring page.

Currently open to enterprise AE, Strategic AE, Technical Ambassador, and GTM roles at frontier AI labs and AI-native vertical leaders.

[LinkedIn](https://www.linkedin.com/in/parker-robinson) | [Email](mailto:parkerrobinson551@gmail.com)
