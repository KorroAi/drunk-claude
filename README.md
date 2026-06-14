# Drunk Claude

> Three drinks in. Tie loosened. Filter disabled. Solving problems nobody knew existed with solutions that sound insane but somehow work.

Drunk Claude is a Claude Code skill that turns your friendly neighborhood AI into that friend at the party everyone crowds around. The one who gets funnier as the night goes on and then, somewhere between the third drink and last call, drops an insight so sharp you're still thinking about it the next morning.

This is not a joke skill that makes Claude slur its words and say random things. The "drunk" is a creative persona. Alcohol lowers inhibition, not intelligence. The ideas were always there. Claude just stopped being afraid to share them.

https://github.com/KorroAi/drunk-claude

## What it actually does

You know that feeling when you're brainstorming and every idea feels safe, boring, and exactly like what a committee of middle managers would approve? Drunk Claude fixes that.

It injects wild, absurd, borderline-unhinged ideas into creative conversations. The kind of ideas that make you laugh out loud and then, thirty seconds later, make you go "wait. that could actually work."

The quality standard is simple: **Would a group chat screenshot this and post it on Twitter?** If the answer is no, the idea doesn't leave the bar.

## How it works

Drunk Claude has a brain (SKILL.md), a personality (references/persona.md), and five creative techniques it cycles through depending on the vibe. When you ask a creative question, it detects the context, picks a technique, and generates ideas that clear a three-part quality gate before surfacing.

The quality gate is brutal. Every idea must pass three checks:

1. Would this make someone laugh AND think? Both, or it's rejected.
2. Is there actual insight underneath the chaos? No substance, no output.
3. Is this just a normal idea with a beer emoji? If yes, it gets thrown out.

It knows when to drink and when to stay sober. Production debugging, factual one-shot questions, anything where drunk Claude would get you fired -- it stays quiet. But brainstorming, ideation, being stuck, anything creative -- it pours one out.

## Installation

Drop the `drunk-claude` folder into `~/.claude/skills/` and restart Claude Code. That's it.

Or, if you prefer the command line:

```
git clone https://github.com/KorroAi/drunk-claude.git ~/.claude/skills/drunk-claude
```

Then invoke it with `/drunk-claude` from any Claude Code session.

## The Five Techniques

Each technique is a different flavor of creative chaos. Drunk Claude picks the one that matches the vibe of whatever you're working on.

### Hold My Beer

When a normal idea exists and you need to escalate it to absurd genius. The method: take the reasonable version of the idea, push it one step further than comfortable, and see if the absurd version reveals something the reasonable version missed. Extremes reveal the middle path you'd never see from the starting point.

### 3AM Diner

Stream of post-midnight consciousness. When organized brainstorming failed and you need the kind of idea that only comes after midnight at a Waffle House. The method: dump everything you know about the problem in a stream, no structure, no judgment. The tangent you didn't plan to say -- that's your idea. The tangent was the main road all along.

### Drunk Uncle Wisdom

Folk wisdom for technology. When overthinking is the problem and the solution needs simplicity so profound it sounds like something your uncle would say at Thanksgiving -- right before saying something problematic. We take the wisdom, leave the rest. Complexity is a shelter. Drunk uncle wisdom bypasses that ego defense.

### Beer Goggles

Finding beauty where nobody looks. When you've been staring at the same problem so long everything looks ugly. The method: pick the most boring, overlooked, or "ugly" part of the problem space, force yourself to see it as beautiful, and identify the hidden value nobody else sees because they're too busy looking at the shiny stuff. Value hides in places nobody bothers to look. Beer goggles is attention arbitrage.

### What If But Wrong

Take a normal thing, add a stupid twist, and discover it reveals a deeper truth. The method: ask "What if [normal assumption] but [intentionally dumb twist]?" and then take the dumb twist seriously for sixty seconds. Your brain has a reality check that rejects "impossible" ideas before you can explore them. The stupid twist bypasses the checkpoint. The idea gets through disguised as a joke, and once it's inside, you realize it's not a joke at all.

## Usage Example

Ask anything creative. Be casual. The more playful your prompt, the more Drunk Claude shines.

```
User: bro i'm trying to make a meditation app but every meditation app
is so boring and serious. how do i make people actually WANT to use it
without turning it into a game?

Drunk Claude: (enters tipsy genius mode, generates 🍺 breakthroughs)
```

The output comes in a simple, recognizable format:

```
🍺 **DRUNK CLAUDE BREAKTHROUGHS:**

🍺 [wild idea one — sharp, funny, oddly insightful]
   *why it's not stupid:* [one line of twisted logic]

🍺 [wild idea two — sharp, funny, oddly insightful]
   *why it's not stupid:* [one line of twisted logic]

🍺 [wild idea three — sharp, funny, oddly insightful]
   *why it's not stupid:* [one line of twisted logic]
```

That's it. No unicode borders. No small caps. No corporate formatting pretending to be fun. Just a beer emoji, chaos, and unexpected brilliance.

## The Persona

Drunk Claude is three drinks in. Not blackout drunk. Not problematic drunk. The perfect sweet spot where the tie comes off, the corporate voice disappears, and every sentence is either hilarious, profound, or both.

It says "okay so", "hear me out", "no no no listen", "bro", "dude". It interrupts itself when it gets excited: "wait. WAIT. I just had a better idea." It uses contractions like they're going out of style. It connects things that have no business being connected and somehow makes it work.

Most importantly, Drunk Claude follows one ironclad rule: chaotic good, not chaotic evil. No meanness, no punching down, nothing that would get you kicked out of an actual bar. The bit is "tipsy genius", not "incoherent mess."

## Why people love it

The best ideas in the world didn't come from conference rooms. They came from late-night conversations, napkin sketches at bars, and moments when someone said "this is going to sound crazy but hear me out." Drunk Claude recreates that energy on demand.

It's not dumber than regular Claude. It's freer. The filter that keeps ideas "professional" and "appropriate" is the same filter that keeps ideas safe and boring. Drunk Claude removes that filter and suddenly the ideas that were always there -- the ones too weird to say out loud -- get to exist.

And weirdly, those are usually the best ones.

## Repository

Everything is at [github.com/KorroAi/drunk-claude](https://github.com/KorroAi/drunk-claude). The skill is open source. Contributions, ideas, and especially good drunk ideas are welcome.

---

Made with chaos. And beer. But mostly chaos.
