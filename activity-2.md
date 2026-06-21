# Activity 2 — Integrated Workflow in Codio

## What you'll do

You're going to build the same artifact you built in Section 1 — same topic, same goal — but this time inside a Codio assignment using the integrated OpenCode environment.

Then you're going to compare the two outputs side by side.

The tool is the same underneath. What changes is everything around it.

---

## Before you start

You'll need:
- Your Codio account (created at the start of the workshop)
- The topic and artifact type you used in Activity 1 (quiz, lesson plan, assignment, rubric — whatever you built)

---

## Step 1 — Create a new Codio assignment

1. Log into your Codio account at [codio.com](https://codio.com)
1. Create a new course
1. Crate a new module in the new course
1. Create a new assignment from scratch
1. Open the integrated OpenCode panel inside the assignment

> The OpenCode environment here is preconfigured. It already has the custom orchestrator, tools, and skills installed. You don't need to set anything up.

---

## Step 2 — Start with your topic, not your prompt

In Section 1 you built a structured prompt before you ran anything.

Here, do the opposite. Start simple:

```
I want to create a [YOUR ARTIFACT TYPE] on [YOUR TOPIC] for my course.
```

That's it. Don't add constraints, format instructions, or context yet.

**Then watch what happens.**

The orchestrator will ask you clarifying questions before it builds anything — automatically. Answer each question specifically. The more specific your answers, the better the output.

> This is the same behavior you triggered manually with the "Do Not Assume" snippet in Section 1. Here it's built into the environment — you don't have to remember to ask for it.

---

## Step 3 — Watch where the output lands

When the orchestrator finishes building, look at where the artifact appears.

Notice:
- It lands directly inside your Codio assignment
- It's already formatted with Codio-specific syntax — try buttons, callout boxes, structured sections
- You didn't copy, paste, or reformat anything
- The assignment context (course structure, platform format) was already known

---

## Step 4 — Build your mini-quiz skill

Now you're going to teach the orchestrator something new.

Tell the orchestrator that you want to create a new skill. The skill will be called "mini-quiz". Give the orchestrator the following information:

* The mini-quiz goes at the end of the assignment
* The mini-quiz is five questions
* The questions should cover the main ideas of the assignment
* The mini-quiz should use a variety of question types: MCQ, FITB, and Parsons

Tell the orchestrator to register the skill after creation.

---

## Compare — Section 1 vs Section 2

| | Section 1 (Local OpenCode) | Section 2 (Integrated Codio) |
|---|---|---|
| **Context** | Empty folder, no course knowledge | Assignment-aware, platform-aware |
| **Prompt needed** | Full structured prompt every time | Start simple, orchestrator asks |
| **Output location** | Terminal / local files | Directly in the Codio assignment |
| **Formatting** | Plain markdown | Codio-ready (try buttons, callouts) |
| **Copy-paste required** | Yes | No |
| **Skill reuse** | Manual — you paste the template | Persistent — skill file stays in assignment |

---

## Debrief questions

Be ready to share one of these:

- What did the orchestrator ask you that your Section 1 prompt didn't cover?
- What would you have had to do manually in Section 1 that happened automatically here?
- Is there anything the local workflow did better?
