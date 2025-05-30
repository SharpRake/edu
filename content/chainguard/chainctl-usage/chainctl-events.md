---
title: "chainctl events"
lead: ""
description: "chainctl events basics"
type: "article"
date: 2025-03-06T08:49:15+00:00
lastmod: 2025-03-06T08:49:15+00:00
draft: false
tags: ["chainctl", "events", "Product"]
images: []
weight: 050
---

This page presents some of the more commonly used `chainctl events` commands. For a full reference of all commands with details and switches, see [chainctl Reference](/chainguard/chainctl/).

There are three commands available: create, delete, and list. We'll start with list to see what subscriptions exist.

## View your event subscriptions

Get a list of all your Chainguard account's subscriptions with:

```shell
chainctl events subscriptions list
```

This will return a list of IDs and SINKs for all of your subscriptions. You know what an ID is. A SINK is an addressable or callable resource that can receive incoming events delivered over HTTPS and will translate the delivered event into a returned response that includes promised information. The style and type of response is set by the SINK.


## Create event subscriptions

To create a new event and subscribe to events in that organization or folder, use:

```shell
chainctl events subscriptions create $SINK_URL
```

Depending on the SINK, you may be prompted to respond to some questions before this action is complete. You can add a `-y` to the command to automatically assume `yes` and run without interaction.


## Delete event subscriptions

To delete an existing event, use:

```shell
chainctl events subscriptions delete $SUBSCRIPTION_ID
```

Depending on the SINK, you may be prompted to respond to some questions before this action is complete. You can add a `-y` to the command to automatically assume `yes` and run without interaction.

## Learn More

Chainguard Academy has several guides on [CloudEvents](/chainguard/administration/cloudevents/). You may find our guide on [Subscribing to Chainguard CloudEvents](/chainguard/administration/cloudevents/events-example/) to be particularly useful for understanding how to work with events from Chainguard.