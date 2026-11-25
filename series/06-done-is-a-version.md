# "Done" Is a Version: How Engineers Already Think Like a Business

*Part 6 of From a Human Need to a Working Company*

---

This is the part that surprised me most. The way I solve engineering problems already *is* the way businesses are built. I had just never named it.

## A task needs four things

When a task goes well, it's rarely because of raw skill alone. Think about taking a class from a great coach. The coach doesn't change your ability overnight. What they give you is context: what to do, in what order, and what "good" looks like.

AI works the same way. The model brings the skill. Whether it succeeds depends on what you give it:

- **Context:** the information, rules and examples it needs
- **Tools:** the access it needs to act
- **Guardrails:** the limits it must stay inside
- **Evaluation:** the check that proves it worked

People and teams are no different. Most failures come from missing context, not missing skill.

## "Done" is a version, not a finish line

At work, I never treat "done" as one big finish line. I phase the work into versions, and every version has its own definition of done:

```
v1 (smallest useful)  →  v2 (expand)  →  v3 (scale)
   each: plan → build → test → release → monitor → learn ↻
```

- **Version 1** solves the core problem for one user or one case, end to end.
- **Every version** passes the same checks before it ships: tests for code, evals for AI, a metric for the business.
- **What breaks in production becomes the input for the next version.**

That's CI/CD. It's also how good businesses grow: small releases that always work, not one big launch.

## Solving any problem in ten steps

1. **Trace it to the need.** Ask "why does this matter?" until you reach a human need.
2. **Define it.** *"Today it's X. We want Y. We'll know by Z."* If you can't write that sentence, don't start.
3. **Find the root cause.** Keep asking "why" until you reach a process you can fix. There may be more than one cause.
4. **Take inventory.** Skill, context, tools, money, time, people.
5. **Check what's doable now.** Do that part first. The gap becomes its own task.
6. **Break it into small pieces.** Each piece gets one owner, one set of context, and one check.
7. **Assign each piece.** You, a person, or an AI agent.
8. **Run the smallest test.** The cheapest version that could prove you wrong.
9. **Troubleshoot.** Change one thing at a time, and rerun.
10. **Save the lesson.** A problem that keeps coming back becomes a playbook, then gets delegated, then automated.

The "ask why" habit comes from Toyota's production system. People who use it well say the real root cause usually points to a broken or missing **process**, not a person.

## Seven places a task breaks

When something fails, check these in order:

| What broke | What you see | Fix |
|---|---|---|
| **Goal** | The output is "fine" but useless | Rewrite the goal and the done-check |
| **Size** | Half-done, messy, drifting | Split it into smaller pieces |
| **Context** | Wrong assumptions, generic output | Add rules, examples, sources |
| **Tools** | Stuck, or making things up | Give access, or do that step by hand |
| **Skill** | Still wrong with perfect context | Upgrade or train the performer |
| **Guardrails** | Unsafe or overreaching | Write the missing rule down |
| **Evaluation** | You can't tell if it worked | Define the metric and a test case |

Goal and size problems look like every other problem, so rule them out first. Context is the most common real cause.

This table works for a failed deploy, a confused AI agent, and a sales pitch that didn't land.

## Try this

Take something you're working on that isn't going well. Write its version 1 in one sentence, with one metric. Then walk down the seven rows and find the first one that's broken.

Fix only that one thing.

*Next: Getting it to people.*

---

*Further reading: [Anthropic, Effective context engineering for AI agents](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents) · [IHI, 5 Whys](https://www.ihi.org/library/tools/5-whys-finding-root-cause)*

---

**Go deeper in my notes:**
- [§4 The task card and the context-engineering rules](https://github.com/Manoj1634/from-a-human-need-to-a-working-company/blob/main/guide.md#4-the-task-model-roles-atoms-and-a-frame)
- [§6 The troubleshooting table with a quick test for each row](https://github.com/Manoj1634/from-a-human-need-to-a-working-company/blob/main/guide.md#6-troubleshooting-seven-places-a-task-breaks)

*All my notes on [GitHub](https://github.com/Manoj1634/from-a-human-need-to-a-working-company) · Connect on [LinkedIn](LINKEDIN_LINK)*

---

[← Part 5: One Person, Every Seat: Why a Company Works Better Together](05-one-person-every-seat.md) · [All parts](README.md) · [Part 7: Getting It to People: Aim, Story, Funding and Selling →](07-getting-it-to-people.md)
