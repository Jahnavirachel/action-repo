# action-repo

This repository is used to trigger GitHub webhook events — Push, Pull Request, and Merge — to a connected Flask endpoint.

## Purpose

To simulate GitHub activity and trigger events that get captured in another repo (`webhook-repo`) via webhooks.

## How It Works

- Pushes to any branch trigger `push` events.
- Creating pull requests triggers `pull_request` events.
- Merging pull requests triggers `merge` events (detected via webhook).

## Events Triggered

- `push`
- `pull_request`
- `pull_request` (closed & merged)



