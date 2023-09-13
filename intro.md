---
layout: default
title: Introduction
description: Nostr Data Vending Machines
---

# Rationale
Nostr can act as a marketplace for data processing, where users request jobs to be processed in certain ways (e.g., "speech-to-text", "summarization", etc.), but they don't necessarily care about "who" processes the data.

This NIP is not to be confused with a 1:1 marketplace; instead, it describes a flow where a user announces a desired output, willingness to pay, and service providers compete to fulfill the job requirement in the best way possible.

# Actors
There are two actors in the workflow described in this NIP:
* Customers (npubs who request a job)
* Service providers (npubs who fulfill jobs)

# Links

* [Podcast between `@pablof7z` and `@theguyswan`](https://www.youtube.com/watch?v=WtpY_pQ3zcI)
* [Vendata.io](https://vendata.io) -- General-purpose DVM client