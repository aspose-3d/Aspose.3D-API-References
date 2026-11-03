---
title: "Aufzählung StencilAction"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.StencilAction Enum. Die Stencil-Testaktionen"
type: docs
weight: 2430
url: /de/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

Die Stencil-Testaktionen

```csharp
public enum StencilAction
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Keep | `0` | Behalte den aktuellen Wert |
| Zero | `1` | Setzt den Stencil-Pufferwert auf 0 |
| Replace | `2` | Setzt den Stencil-Puffer auf ref, wo in [`StencilReference`](../renderstate/stencilreference/) definiert |
| Increment | `3` | Erhöht den aktuellen Stencil-Pufferwert und begrenzt ihn auf den Maximalwert. |
| IncrementWrap | `4` | Erhöht den aktuellen Stencil-Pufferwert und setzt ihn auf Null zurück, wenn er den Maximalwert erreicht. |
| Decrement | `5` | Erhöht den aktuellen Stencil-Pufferwert und begrenzt ihn auf 0. |
| DecrementWrap | `6` | Verringert den aktuellen Stencil-Pufferwert und setzt ihn auf den Maximalwert zurück, wenn er Null erreicht. |
| Invert | `7` | Invertiert den aktuellen Stencil-Pufferwert bitweise. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


