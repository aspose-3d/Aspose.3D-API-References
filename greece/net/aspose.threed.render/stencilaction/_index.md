---
title: "Απαρίθμηση StencilAction"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.StencilAction enum. Οι ενέργειες δοκιμής στένσιλ"
type: docs
weight: 2430
url: /el/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

Οι ενέργειες δοκιμής στίλας

```csharp
public enum StencilAction
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Keep | `0` | Διατηρήστε την τρέχουσα τιμή |
| Zero | `1` | Ορίζει την τιμή του buffer στένσιλ σε 0 |
| Replace | `2` | Ορίζει το buffer στένσιλ σε ref όπου ορίζεται στο [`StencilReference`](../renderstate/stencilreference/) |
| Increment | `3` | Αυξάνει την τρέχουσα τιμή του buffer στένσιλ, περιορίζεται στη μέγιστη τιμή. |
| IncrementWrap | `4` | Αυξάνει την τρέχουσα τιμή του buffer στένσιλ και την επαναφέρει στο μηδέν όταν φτάσει τη μέγιστη τιμή. |
| Decrement | `5` | Αυξάνει την τρέχουσα τιμή του buffer στένσιλ, περιορίζεται στο 0. |
| DecrementWrap | `6` | Μειώνει την τρέχουσα τιμή του buffer στένσιλ και την επαναφέρει στη μέγιστη τιμή όταν φτάσει στο μηδέν. |
| Invert | `7` | Αντιστρέφει λογικά την τρέχουσα τιμή του buffer στένσιλ. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


