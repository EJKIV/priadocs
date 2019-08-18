---
category: Event Tracking
title: 'Client Side Events'

layout: nil
---

These events are collected in the web app and native applications.

# Account Created

## Devices

**`iOS`**  **`Android`** 

## Purpose

Key event for initial user engagement

## Properties

```

    type: 'invite" || 'organic' || 'marketing'

```

## Location

## New Account 1/2

```

analytics.track('Signed Up', {
  type: 'invite' || 'organic'
});

```

## Status

<button class='success'>Ready</button>
<button class='warning'>Installed</button>
<button class='danger'>Tested</button>