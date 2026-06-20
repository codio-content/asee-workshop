# Structured Prompt Reference Card

A structured prompt has seven components. Most people include two or three. The difference in output quality is significant.

---

## The Seven Components

| Component | What it does | Example |
|---|---|---|
| **Role** | Tells the AI what kind of expert to be | "You are an experienced instructional designer..." |
| **Task** | States what you want built | "Create a 5-question quiz on..." |
| **Audience** | Describes who this is for | "First-year undergraduates who know variables but not loops" |
| **Learning objective** | Anchors output to a measurable outcome | "Students will be able to trace a for loop and predict output" |
| **Prior knowledge** | Defines what to build on and what to avoid | "Students know conditionals. They haven't seen recursion." |
| **Constraints** | Sets boundaries on format, length, complexity | "No more than 5 questions. No code-writing required." |
| **Output format** | Specifies exactly how you want the result structured | "Numbered questions, A/B/C/D options, answer key at the end" |

---

## Full Template

```
You are [ROLE].

Task: [WHAT YOU WANT BUILT — be specific about topic and artifact type].

Audience: [WHO — year, course, prior experience].

Learning objective: [What should students be able to do?]

Prior knowledge: Students already know [X]. They have not yet covered [Y].

Constraints:
- [CONSTRAINT 1]
- [CONSTRAINT 2]
- [CONSTRAINT 3]

Output format:
- [FORMAT DETAIL 1]
- [FORMAT DETAIL 2]
- [FORMAT DETAIL 3]
```

---

## With the "Do Not Assume" snippet

For best results, prepend the snippet from `prompts/do-not-assume.md` before this template:

```
Before you begin, ask me questions about anything that is unclear
in this task. Do not make assumptions. Only begin building once
you have asked all your questions and I have answered them.

---

You are [ROLE].

Task: [TASK]

Audience: [AUDIENCE]

Learning objective: [OBJECTIVE]

Prior knowledge: [PRIOR KNOWLEDGE]

Constraints:
- [CONSTRAINT 1]
- [CONSTRAINT 2]

Output format:
- [FORMAT DETAIL 1]
- [FORMAT DETAIL 2]
```

---

## What to expect as you improve

| Prompt type | Typical first-draft usability |
|---|---|
| Naive ("make me a quiz") | 10–20% — heavy editing required |
| Structured (no snippet) | 50–70% — moderate editing |
| Structured + "do not assume" | 70–90% — light editing or ready to use |

These aren't guarantees — they depend on how specific your inputs are. The more specific, the higher the floor.

---

## Save this as a skill file

Once you've adapted this template for your course, save it as a `.md` file in a `/skills` folder in your project. Give it to OpenCode at the start of any session with:

```
Read skills/my-course-prompt.md before we begin.
```

It will know your context without you re-typing it every time. See `skills/lesson-plan.md` for an example.
