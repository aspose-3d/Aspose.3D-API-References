---
title: "Enum StencilAction"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.StencilAction enum. Les actions du test de pochoir"
type: docs
weight: 2430
url: /fr/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

Les actions du test stencil.

```csharp
public enum StencilAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Keep | `0` | Conserver la valeur actuelle |
| Zero | `1` | Définit la valeur du tampon de pochoir à 0 |
| Replace | `2` | Définit le tampon de pochoir à ref où il est défini dans [`StencilReference`](../renderstate/stencilreference/) |
| Increment | `3` | Incrémente la valeur actuelle du tampon de pochoir, la limite à la valeur maximale. |
| IncrementWrap | `4` | Incrémente la valeur actuelle du tampon de pochoir et la ramène à zéro lorsqu'elle atteint la valeur maximale. |
| Decrement | `5` | Incrémente la valeur actuelle du tampon de pochoir, la limite à 0. |
| DecrementWrap | `6` | Décrémente la valeur actuelle du tampon de pochoir et la ramène à la valeur maximale lorsqu'elle atteint zéro. |
| Invert | `7` | Inversion bit à bit de la valeur actuelle du tampon de pochoir. |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


