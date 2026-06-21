# Integrated Workflow — Reference Guide

This file explains what the integrated OpenCode environment inside Codio is doing and why it produces different results than running OpenCode locally.

Keep this open as a reference during Activity 2 and after the workshop.

---

## What "integrated" actually means

When you run OpenCode locally (Section 1), the AI sees:
- Whatever files are in the folder you opened it from
- Whatever you type in the prompt
- Nothing else

When you run OpenCode inside a Codio assignment, the AI sees:
- The structure of your assignment
- The platform it's publishing to and its formatting requirements
- A set of pre-installed tools, skills, and an orchestrator agent configured for course authoring

The underlying model is the same. The context it operates in is completely different.

---

## The orchestrator

The integrated environment has a custom orchestrator agent that manages the build process. It does three things automatically that you had to do manually in Section 1:

**1. Clarifying questions before building**
It enters plan mode before it generates anything. It asks about audience, format, length, and constraints. You don't need to remember the "Do Not Assume" snippet — this behaviour is built in.

**2. Platform-aware output**
It knows it's building for Codio. Output arrives already formatted with Codio-specific syntax — try buttons, callout boxes, structured assessment blocks. You don't reformat anything.

**3. Assignment context**
It knows where in the assignment the artifact should live. It writes directly to the right place. Nothing leaves the platform.

---

## The skill system

Skills in the integrated environment work the same way as in Section 1 — they're `.md` files that give the AI standing context. The difference is persistence.

In Section 1, you had to reference your skill file manually at the start of every session. In Codio, you use the "Skill Builder" which is part of the Open Code orchestrator that creates everything in the right format based on your specifications and once you're set, you ask it to register so it's available in that assignment to use.

You build a skill once. It applies every time.

---

## What this fixes from Section 1

| Problem in Section 1 | How the integrated environment addresses it |
|---|---|
| Had to write a full structured prompt every time | Orchestrator asks clarifying questions — start simple |
| Output was plain markdown in a local file | Output lands directly in the assignment, Codio-formatted |
| No course context unless you typed it | Assignment structure is already known |
| Skill files referenced manually | Skill files persist automatically |
| Copy-paste to get content into the platform | No copy-paste — everything stays in Codio |

---

## What the integrated environment does NOT change

- You still need to review and edit the output — the AI is a first-draft tool, not a final-draft tool
- You still own the pedagogy — the orchestrator builds what you ask for, not what's educationally sound
- Skills still need to be written by you — the environment doesn't know your course preferences until you tell it

---

## After the workshop

Everything you build in the Codio assignment during this workshop stays in your account. You can:
- Continue building on the same assignment
- Duplicate it as a template for other courses
- Export the skill files and use them in new assignments

Your free instructor account at codio.com/workshop gives you full access to the authoring environment.
