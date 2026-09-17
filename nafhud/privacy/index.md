---
layout: page
title: Privacy policy
description: How nafhud accesses, uses, stores, and shares Google account data for Stefan Mai's personal workflows.
permalink: /nafhud/privacy/
section: Privacy
updated: September 17, 2026
---

This policy covers **nafhud**, a personal Mac and iPhone application built and operated by Stefan Mai. nafhud is used by Stefan with his own connected accounts; it does not offer public signup.

## Google data accessed

With authorization, nafhud uses the Gmail API's read-only scope (`gmail.readonly`) to detect new incoming messages. It accesses account identifiers and message metadata, including message and thread IDs, sender and recipient addresses, subjects, labels, and timestamps. Message bodies may be fetched on demand when a personal workflow needs their content.

This authorization does not allow the Gmail integration to send, alter, or delete mail.

## How data is used

Google data is used to support Stefan's personal workflows: recognizing an expected reply or notification, continuing a waiting agent session, processing incoming messages, preparing a follow-up, and creating personal todos. A local routing record tracks message handling so workflows can coordinate their work.

nafhud does not sell Google account data or use it for advertising.

## Storage and security

A bridge running on Stefan's Mac polls Gmail and stores message metadata and routing records locally. OAuth refresh tokens are stored in macOS Keychain. Relevant message content may also appear in agent session history or in the outputs of an authorized workflow, such as a todo or a draft.

## Agent providers and sharing

When Stefan uses a Claude or Codex session to handle a message, relevant metadata or message content may be sent to the corresponding provider, Anthropic or OpenAI, to carry out that workflow. **Email processed by an agent is therefore not kept exclusively on the Mac.** Provider processing and retention depend on the service, account settings, and applicable provider terms.

Google data is not published on this website. This policy does not authorize an agent to send a message to another person; outbound actions remain subject to Stefan's instructions.

## Retention and deletion

Local message metadata, routing records, and workflow outputs are retained until Stefan removes them. There is no automatic deletion period promised by this policy. Content already included in an agent session is also subject to that provider's retention and deletion controls.

Removing stored credentials or revoking Google access stops future authorized access, but does not automatically erase previously stored data or existing workflow outputs. Stefan can remove local records and use the relevant provider's controls to manage session data. Questions or requests about stored data can be sent to [iamnafets@gmail.com](mailto:iamnafets@gmail.com).

## Revoking Google access

Access can be revoked in [Google Account connections](https://myaccount.google.com/connections). Select nafhud and remove its access. To resume Gmail workflows after revocation, Stefan must authorize the connection again.

## Google API data

Use and transfer of data received from Google APIs are subject to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements. Google data is used for the personal features described in this policy.

## Changes and contact

This page will be updated when nafhud's data handling changes. The date above identifies the latest update.

**Operator:** Stefan Mai

**Contact:** [iamnafets@gmail.com](mailto:iamnafets@gmail.com)

<div class="policy-links"><a href="{{ '/nafhud/' | relative_url }}">About nafhud</a><a href="{{ '/nafhud/terms/' | relative_url }}">Terms of use</a></div>
