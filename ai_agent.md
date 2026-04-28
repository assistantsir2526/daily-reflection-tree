# AI Agent Design

## Overview

This AI agent helps users reflect on their daily productivity using a rule-based approach.

## How it works

1. It asks structured questions.
2. It maps user responses to fixed outputs.
3. It provides one clear improvement suggestion.

## Guardrails to prevent hallucination

* Only predefined inputs are accepted
* No assumptions are made
* No random responses are generated
* Same input always gives same output

## Example

Input: "No, I was distracted"
Output: "Eliminate distractions and create a focused workspace"
