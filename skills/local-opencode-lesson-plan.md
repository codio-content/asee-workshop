# Skill: Lesson Plan Generator

This is a reusable skill file. Save it in your project's `/skills` folder and reference it at the start of any OpenCode session to give the AI standing context about your course without re-typing it every time.

---

## How to use this file

At the start of an OpenCode session, say:

```
Read skills/lesson-plan.md before we begin. Ask me any questions
you have about my course context before we start the task.
```

Then give your task. The AI will use everything in this file as background.

---

## How to customise it

Replace everything in `[BRACKETS]` with your own course details. The more specific you are, the better the output. Delete any sections that don't apply to your context.

---

## Your Course Context

```
Course name: [e.g. Introduction to Computer Science — CS101]
Institution: [e.g. State University]
Level: [e.g. First-year undergraduate]
Class size: [e.g. 35 students]
Format: [e.g. In-person lecture + lab, 2x per week]
Platform: [e.g. Codio / Canvas / Blackboard / none]

Typical student profile:
- [e.g. Mixed backgrounds — some have programming experience, most do not]
- [e.g. Majority are engineering majors taking this as a requirement]
- [e.g. Comfortable with spreadsheets, limited exposure to code]

Topics covered so far this semester:
- [TOPIC 1]
- [TOPIC 2]
- [TOPIC 3]

Topics not yet covered (do not assume knowledge of these):
- [TOPIC A]
- [TOPIC B]

Course learning outcomes:
1. [OUTCOME 1]
2. [OUTCOME 2]
3. [OUTCOME 3]

Assessment types used in this course:
- [e.g. Weekly quizzes (auto-graded, multiple choice + short answer)]
- [e.g. Programming assignments (submitted via Codio)]
- [e.g. Midterm and final exam (in-person)]

Tone and accessibility preferences:
- [e.g. Language should be accessible to students new to programming]
- [e.g. Avoid jargon without definition]
- [e.g. Include one worked example before asking students to try independently]
```

---

## Standing output preferences

```
When generating lesson content for this course:
- Use Markdown formatting with clear headings
- Include a learning objective at the top of every lesson
- Flag any prerequisite knowledge students will need
- Include at least one formative check per lesson
- Keep explanations concise — students read on screen, not on paper

When generating assessments:
- Always include an answer key
- Include a one-sentence explanation for each correct answer
- Flag any question that might trip up students who missed a prior concept
```

---

## Example session opener

Once you've filled in your course details above, start an OpenCode session like this:

```
Read skills/lesson-plan.md. Ask me any clarifying questions about
my course before we begin.

Task: Create a 20-minute in-class activity on [TOPIC] for next Tuesday's lecture.
The activity should include a warm-up, a worked example, and a formative check.
Output as Markdown, ready to paste into my course notes.
```
