---
layout: default
title: hostinnetgroup
---

[%CFEngine_function_prototype(netgroup)%]

**Description:** True if the current host is in the named `netgroup`.

[%CFEngine_function_attributes(netgroup)%]

**Example:**

```cf3
classes:

  "ingroup" expression => hostinnetgroup("my_net_group");
```
