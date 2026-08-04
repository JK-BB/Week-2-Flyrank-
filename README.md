Assigment1
# AI Workflow Comparison

## Overview

This project compares two different ways of building the same feature using AI. The goal was to understand how the quality of a prompt influences the quality of the generated code and how much manual review is required.

The feature chosen for this comparison is a user settings form with validation.

## Feature

The settings form includes:

- Name field
- Email field with validation
- Theme selection (Light/Dark)
- Notification toggle
- Save button
- Responsive design

## Development Approaches

### Branch 1 – `feature/settings-vague`

This version was created using a simple, high-level prompt with very little guidance.

Prompt used:

> Build a simple settings page with a form where users can edit their name, email, theme preference, and notification settings.

The generated code worked but required additional review and improvements before it could be considered complete.

### Branch 2 – `feature/settings-spec`

This version was built using a detailed prompt that included:

- project context
- implementation plan
- validation requirements
- accessibility guidelines
- design constraints
- edge cases
- self-review and verification

Providing clear instructions resulted in cleaner, more reliable code with fewer manual changes.

## Key Findings

Comparing both approaches showed that:

- Detailed prompts produced more accurate results.
- Validation and accessibility were handled more effectively.
- The generated code was easier to maintain.
- Less time was spent fixing mistakes during review.

The complete comparison is documented in **WORKFLOW.md**.

## Files

- `README.md` – Project overview
- `WORKFLOW.md` – Workflow comparison and observations
- `CLAUDE.md` – Project-specific AI rules

## Technologies Used

- HTML
- CSS
- JavaScript
- Claude AI

## Conclusion

This exercise demonstrated that successful AI-assisted development depends on clear instructions rather than relying on AI to make assumptions. Treating AI as a collaborative development tool—through planning, verification, and review—led to better quality code and a smoother development process.
