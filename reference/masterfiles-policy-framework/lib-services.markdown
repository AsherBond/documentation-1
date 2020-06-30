---
layout: default
title: lib/services.cf
published: true
tags: [reference, standard library, services, MPF]
---

See the [`services` promises][services] documentation for a
comprehensive reference on the body types and attributes used here.

To use these bodies and bundles, add the following to your policy:

```cf3
body file control
{
	inputs => { "services.cf" }
}
```

[%CFEngine_library_include(lib/services)%]
