---
title: "EventStoreDB"
description: "Subscriptions for EventStoreDB"
date: 2021-04-28
draft: false
weight: 530
images: []
---

[EventStoreDB](https://eventstore.com) natively supports real-time subscriptions, which will also deliver historical events when you don't specify the starting position. It makes the product a perfect candidate to support event-sourced systems, as you won't need to invent things like CDC- or pull-based subscriptions.

Eventuous supports all subscription kinds provided by EventStoreDB: