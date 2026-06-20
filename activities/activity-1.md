# Activity 1 — Best Practices for Generic AI Tools

## What you'll do

Two beats. Same tool (OpenCode). Very different results.

---

## Beat 1 — The Naive Prompt

Open OpenCode and type this exactly as written. Don't add anything.

```
Create a quiz for my students.
```

Run it. Look at what you get.

**Ask yourself:**
- Is this usable as-is?
- What's missing?
- How much editing would you need to do before putting this in front of students?

---

## Beat 2+3 — The Structured Prompt

Now you're going to rebuild the same request — but properly.

There are two parts to this:

1. The **"Do Not Assume" snippet** goes at the very top. It tells the AI to ask you clarifying questions before it builds anything.
2. The **structured prompt** gives the AI the context it needs to do the job well.

---

### Filled Example
*(Read this first so you know what good looks like — then use the blank template below for your own course)*

```
Before you begin, ask me questions about anything that is unclear
in this task. Do not make assumptions. Only begin building once
you have asked all your questions and I have answered them.

---

You are an experienced instructional designer helping a university
computer science instructor.

Task: Create a short quiz on the topic of loops in Python.

Audience: First-year undergraduate students in an introductory
programming course (CS101).

Learning objective: Students will be able to trace a for loop
and predict its output given specific input values.

Prior knowledge: Students have covered variables, print statements,
and basic conditionals. They have not yet seen while loops or
nested loops.

Constraints:
- 5 questions maximum
- Mix of multiple choice and short answer
- No questions requiring students to write code from scratch
- Language should be accessible to students new to programming

Output format:
- Each question numbered
- Multiple choice options labeled A, B, C, D
- Correct answer and one-sentence explanation included after each question
- Estimated time to complete: under 10 minutes
```

---

### Your Turn — Blank Template

Copy everything below into OpenCode. Fill in the `[BRACKETED]` sections for something real from your own course. Keep the "Do Not Assume" lines exactly as written at the top.

```
Before you begin, ask me questions about anything that is unclear
in this task. Do not make assumptions. Only begin building once
you have asked all your questions and I have answered them.

---

You are [ROLE — e.g. "an experienced instructional designer helping a university instructor"].

Task: Create a [ARTIFACT TYPE — e.g. quiz / lesson plan / assignment / rubric] on the topic of [TOPIC].

Audience: [WHO — e.g. "second-year undergraduate students in a data structures course"].

Learning objective: [What should students be able to do after this?]

Prior knowledge: Students already know [X]. They have not yet covered [Y].

Constraints:
- [CONSTRAINT 1 — e.g. length, format, reading level]
- [CONSTRAINT 2]
- [CONSTRAINT 3]

Output format:
- [FORMAT DETAIL 1 — e.g. numbered questions, rubric rows, section headings]
- [FORMAT DETAIL 2]
```

---

## What to expect

When you run the filled template, the AI should respond with **questions** before it builds anything. That's the "Do Not Assume" snippet working. Answer the questions in the chat. Then it will build.

Compare what you get to Beat 1. Notice:
- Did the AI ask you something that improved the output?
- Is this closer to something you could actually use?
- How much editing would you still need to do?

---

## Debrief question

Be ready to share one thing the AI asked you — and whether answering it changed what got built.
