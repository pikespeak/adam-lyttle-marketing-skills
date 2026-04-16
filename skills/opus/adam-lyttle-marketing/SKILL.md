---
name: adam-lyttle-marketing
description: "Use when planning or critiquing solo app strategy using Adam Lyttle's approach: app idea validation, market and keyword research, lean execution, deadline-based building, App Store launches, ASO, launch-week download velocity, X/Twitter community distribution, or in-app word-of-mouth loops."
---

# Adam Lyttle Marketing

## Overview

Apply Adam Lyttle's solo app model: set a concrete challenge, validate demand before build, prove the core mechanic, ship with tight constraints, position for App Store search, concentrate launch-week downloads, use social/community distribution, and design shareable product moments.

## Core Workflow

1. Start with distribution, not copy. Identify the target user, the primary search phrase, existing demand, competition, and the channels that can drive launch-week downloads.
2. Validate the idea in layers: inspiration and goal, rough concept, technical proof of concept, market validation, then refinement or pivot.
3. Build under constraints. Use a real deadline, a launch-critical task list, and a "then list" for polish, cosmetic work, and non-critical features.
4. Protect the core flow. Build rigid functionality first, test the simplest version, reduce menus and pauses, and throw users back into the main use case.
5. Build ASO into the product plan. Choose one primary keyword for 90% of ASO focus, put its exact phrase in the title, put secondary terms in the subtitle without repeating title words, and keep the wording human-readable.
6. Plan the first week as the ranking window. Treat the first days and weeks as a download-velocity event that can influence App Store trajectory for months.
7. Use a narrow visibility campaign at launch when relevant. For App Store apps, consider Apple Search Ads exact-match ads for the app title/brand terms as soon as the app is approved; turn Search Match off, avoid broad match, monitor spend, and stop once indexed/ranking.
8. Promote beyond the store. Launch on X/community channels with a goal-driven builder hook and a user-facing product hook. Treat launch day like Product Hunt: multiple interesting posts, not repetitive spam.
9. Design word-of-mouth into the app. Find the pause point users will screenshot or share, brand it, make it emotionally rewarding, and add a direct share action when possible.

## Required Checks

- If the app idea is not validated, flag that marketing starts at validation. Do not invent keywords after the product is already fixed without calling out the risk.
- If the concept has no proof of concept, recommend a fast prototype before market-facing launch planning.
- If scope is growing, separate launch-critical tasks from the then list and force a real deadline with consequences.
- If recommending paid ads, scope them as a launch visibility tactic, not an open-ended acquisition strategy. Include exact-match targeting, Search Match off, spend monitoring, and shutoff criteria.
- If writing launch copy, include both hooks: a public goal for the builder/community audience and a concrete product reason for normal users.
- If suggesting social launch activity, require multiple distinct post angles: announcement, context/story, demo, build insight/tutorial, competition or challenge, and progress updates.
- If suggesting growth loops, specify what users share, why they care emotionally, where branding appears, and how the shared artifact drives installs.

## Output Shape

For planning requests, return:

- Idea thesis: goal, target market, proof-of-concept status, market demand, competition, pivot risks.
- Build plan: deadline, launch-critical 80%, then list, flow risks, feedback plan.
- ASO thesis: primary keyword, title, subtitle, secondary terms, risks.
- Launch week plan: approval moment, visibility campaign, external promotion, download velocity targets, monitoring.
- Social/community plan: launch post angle, supporting post angles, community actions.
- Word-of-mouth loop: shareable moment, branded artifact, share trigger, expected effect.
- Gaps and assumptions: missing demand data, unclear audience, budget risk, dependency on one channel.

## Reference

Read the relevant reference before detailed work:

- `references/idea-validation.md` for idea generation, proof-of-concept, keyword demand, competition, and pivot decisions.
- `references/execution-and-building.md` for deadlines, 80/20 shipping, then lists, code massaging, feedback, flow, and design vision.
- `references/launch-and-marketing.md` for ASO, Apple Search Ads visibility, launch posts, download velocity, and word-of-mouth loops.
