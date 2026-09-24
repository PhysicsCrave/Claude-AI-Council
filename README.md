# AI Council

A Claude skill that turns any question or decision into a council meeting. Type `council this` (or just `council`) and five advisors weigh in, then a Chairman gives a verdict.

## The advisors

1. **The Contrarian** pressure-tests the idea and names exactly what could fail.
2. **The First Principles Thinker** asks whether you're solving the right problem.
3. **The Expansionist** finds the hidden upside and the bigger version.
4. **The Outsider** brings a view from a completely different field.
5. **The Executor** tells you what to actually do Monday morning.

Each speaks in 3 to 5 sentences, and they're expected to disagree.

## The Chairman

The Chairman is deliberately cautious. It gives the Contrarian's risks real weight and prefers cheap, reversible steps over big bets. It still takes a clear position and says what would change it. Every verdict has three parts:

- **The one thing to do**
- **The biggest risk to watch**
- **The first step**

## Install

Add the `ai-council` folder to your Claude skills, or upload `SKILL.md` as a custom skill in Claude's settings.

## Usage

```
council this: should I apply Early Decision to my top-choice school?
```

Typing `council` on its own runs the council on the last question or plan in the conversation.
