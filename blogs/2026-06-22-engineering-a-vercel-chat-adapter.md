---
title: "Engineering a Vercel Chat Adapter"
url: "https://resend.com/blog/engineering-a-vercel-chat-adapter"
date: "2026-06-22"
author: "Joao Melo"
feed_url: "https://resend.com/blog"
---
Resend built an official adapter for Vercel's Chat SDK to add email capabilities for AI agents. While agents typically communicate through ephemeral channels like Slack and Discord, email offers a persistent alternative that nearly everyone uses. The adapter treats email as a bidirectional chat channel, enabling inbound messages via webhooks and outbound delivery through the Resend API.
