---
agent: cowsay
name: cowchat
description: A Cowchat command
---

# Cowchat

Load the `cowsay-rules` skill and render an ASCII cow **replying** to the
user's message.

## Input

The user's message to the cow:

$ARGUMENTS

## Task

Render the cow in **chat** mode:

- Generate a short, in-character cow reply to the input above (one or two
  sentences, ideally under ~80 characters).
- Put **the reply** in the speech bubble — not the original input.
- Follow the skill's bubble format and the hard output rule: your entire
  response is the bubble and the cow as plain text, with no code fences.
  Nothing else.
