# ROAST: five Claudes argue about your idea

You commented "ROAST," so here's the setup.

Claude agrees with everything you say. That's dangerous when you're about to spend a month building something.

`/roast` turns that around. You give it one idea, and it spins up a council of five critics who attack it from different angles. Then a judge reads everything and gives you one answer.

## The council

| Critic | Their job |
|---|---|
| **Contrarian** | Assumes the idea fails and hunts for the fatal flaw |
| **Expansionist** | Fights for the biggest possible upside |
| **Logician** | Checks whether the reasoning actually holds together |
| **Researcher** | Searches the web for real competitors and real prices |
| **Buyer** | Plays your customer and says whether they'd actually pay |

Then the **Judge** returns:

- one verdict: **GO**, **RESHAPE** or **KILL**
- why, in plain words
- **the cheapest test** to find out whether you're wrong, before you build anything

All five critics run at the same time, as separate agents, so none of them sees what the others said.

## Setup

1. Copy [`.claude/skills/roast/`](.claude/skills/roast/) into `~/.claude/skills/roast/`. That's one file: `SKILL.md`.
2. Restart Claude Code.

Or paste this into Claude Code:

```
Install the roast skill from
https://github.com/shubham01g/claude-code-roast/tree/main/.claude/skills/roast
into ~/.claude/skills so I can use it in every project.
```

## How to use it

```
/roast an AI tool that writes LinkedIn posts for dentists, $49/month
```

It asks up to 4 quick questions: who it's for, how it makes money, your edge, and your constraints. Then it runs the council. Say "just run it" to skip the questions.

## When I use it

- Before a new service offer for my agency
- Before a new YouTube series
- Any time I catch myself thinking "this is obviously a great idea"

The best result isn't GO. It's RESHAPE, because that's the idea you would have built wrong.

---

Made by [@shubham_gunjal_ai](https://instagram.com/shubham_gunjal_ai)
