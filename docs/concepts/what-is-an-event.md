---
id: what-is-an-event
title: What is an Event?
sidebar_label: Event
description: Events are created by the Temporal Cluster in response to external occurrences and Commands generated by a Workflow Execution.
tags:
  - term
  - explanation
---

Events are created by the Temporal Cluster in response to external occurrences and Commands generated by a Workflow Execution. Each Event corresponds to an `enum` that is defined in the [Server API](https://github.com/temporalio/api/blob/master/temporal/api/enums/v1/event_type.proto).

All Events are recorded in the [Event History](/concepts/what-is-an-event-history).

A list of all possible Events that could appear in a Workflow Execution Event History is provided in the [Event reference](/references/events).
