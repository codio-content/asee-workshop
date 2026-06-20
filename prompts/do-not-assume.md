# The "Do Not Assume" Starter Snippet

Paste this at the **very top** of any non-trivial prompt before you add your task.

```
Before you begin, ask me questions about anything that is unclear
in this task. Do not make assumptions. Only begin building once
you have asked all your questions and I have answered them.
```

---

## Why it works

Without this snippet, the AI fills in gaps with its best guess. Those guesses are often wrong — wrong audience, wrong format, wrong length, wrong constraints. You then spend time correcting a draft that was built on bad assumptions.

With this snippet, the AI surfaces its assumptions as questions *before* it builds. You answer them. The first draft reflects your actual requirements.

The result: fewer revision rounds, more usable first drafts.

---

## When to use it

Use it for any task where the output needs to fit a specific context — lesson plans, assignments, rubrics, quiz questions, feedback templates. 

Skip it for quick, low-stakes tasks where the defaults don't matter — summarising a paragraph, generating a list of synonyms, reformatting text.

---

## Tips

- **Answer questions specifically.** Vague answers ("intermediate students") produce vague output. Specific answers ("students who have covered variables and conditionals but not loops") produce usable output.
- **It's okay to say "I don't know."** If the AI asks something you haven't decided yet, say so. It will either make a reasonable choice or ask a follow-up.
- **You can add constraints mid-conversation.** If the first draft is close but not quite right, add a constraint and ask it to revise. You don't have to start over.

---

## Combine it with a structured prompt

The snippet works best when paired with a structured prompt that gives the AI role, task, audience, and output format. See `prompts/structured-prompt.md` for the full template.
