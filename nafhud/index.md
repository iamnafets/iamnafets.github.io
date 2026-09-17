---
layout: page
title: nafhud
description: Stefan Mai's personal Mac and iPhone workspace for agent sessions, tasks, and email follow-ups.
permalink: /nafhud/
section: Personal software
---
<p class="lede">My personal workspace for tasks, agent sessions, and the things I'm waiting on.</p>

nafhud is software I build and use on my Mac and iPhone. It connects my personal tasks and Claude and Codex sessions with a bridge running on my Mac, so work can continue when the next piece arrives.

<div class="notice">nafhud is for Stefan Mai's personal use. It is not a public service, and there is no public signup.</div>

## Why it connects to Gmail

Some work needs a reply before it can move forward. nafhud uses read-only Gmail access to detect incoming email in my connected Google accounts and route a message to the agent or workflow waiting for it. Other incoming messages can enter personal workflows, such as creating a todo or preparing a follow-up.

The Gmail integration can read messages. It cannot send mail, modify messages, or delete email through its read-only authorization.

## How email is handled

1. A bridge on my Mac checks Gmail for new messages and saves message metadata locally.
2. A routing record tracks which personal workflow is handling each message.
3. Message bodies can be fetched when needed. When a workflow uses an agent, relevant email content may be processed in my Claude or Codex sessions by the corresponding model provider.

OAuth refresh tokens are stored in macOS Keychain. Google account access can be revoked at any time. The [privacy policy]({{ '/nafhud/privacy/' | relative_url }}) explains storage, provider processing, retention, and revocation.

## Contact

Built and operated by Stefan Mai. Questions about nafhud or its use of Google data can be sent to [iamnafets@gmail.com](mailto:iamnafets@gmail.com).

<div class="policy-links"><a href="{{ '/nafhud/privacy/' | relative_url }}">Privacy policy</a><a href="{{ '/nafhud/terms/' | relative_url }}">Terms of use</a></div>
