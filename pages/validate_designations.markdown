---
layout: page
title: Clip Validation
permalink: /validation/
nav_order: 3
---

### Clip Validation

One of the major features of Clip Creator is clip validation.  Each clip is checked individually for range errors, and against the growing populaiton for potential conflicts.  Below we see an Overlap error, where the new designation overlaps with an existing one:

> ![Animation - Merge Overlap Error](../assets/manualClipEntry_mergeOverlap.gif)

When the Merge Designations option is selected, Clip Creator combines the two designations, taking the earliest starting page:line value and the latest ending page:line and replacing the existing clip with the new.

In addition to the overlap error, each new clip is checked against the population for:

> - **Subset Range** - New clip is appears wholy inside an existing clip
> - **Superset Range** - New clip encompases an existing clip
> - **Duplicate Range** - New clip has the same range as an existing clip
> - **Duplicate ID** - New clip has the same ID as an existin clip