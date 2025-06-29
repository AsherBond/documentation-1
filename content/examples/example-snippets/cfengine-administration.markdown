---
layout: default
title: Administration examples
sorting: 2
---

* [Ordering promises][Administration examples#Ordering promises]
* [Aborting execution][Administration examples#Aborting execution]

## Ordering promises

This counts to five by default. If we change '/bin/echo one' to '/bin/echox one', then the command will fail, causing us to skip five and go to six instead.

This shows how dependencies can be chained in spite of the order of promises in the bundle.

Normally the order of promises in a bundle is followed, within each promise type, and the types are ordered according to normal ordering.


[%CFEngine_include_snippet(ordering_promises.cf, .* )%]

## Aborting execution

[%CFEngine_include_snippet(aborting_execution.cf, .* )%]
