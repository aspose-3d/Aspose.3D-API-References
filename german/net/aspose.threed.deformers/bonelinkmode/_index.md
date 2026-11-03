---
title: "Enum BoneLinkMode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Deformers.BoneLinkMode Enum. Ein Knochenverbindungsmodus bezieht sich auf die Art und Weise, wie ein Knochen mit seinem übergeordneten Knochen innerhalb einer hierarchischen Struktur verbunden oder verknüpft ist."
type: docs
weight: 200
url: /de/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

Der Verknüpfungsmodus eines Knochens bezieht sich auf die Art und Weise, wie ein Knochen mit seinem übergeordneten Knochen innerhalb einer hierarchischen Struktur verbunden oder verknüpft ist.

```csharp
public enum BoneLinkMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Normalize | `0` | In diesem Modus werden die Transformationen von Kindknochen in Bezug auf die Transformationen ihres Elternknochens normalisiert. |
| Additive | `1` | Der additive Modus berechnet die Transformationen von Kindknochen, indem er deren eigene lokale Transformationen zu denen ihrer Elternknochen hinzufügt. |
| TotalOne | `2` | Total One stellt sicher, dass die kombinierten Transformationen von Eltern‑ und Kindknochen zu einer kombinierten Transformation führen, die auf eine Gesamtlänge von einer Einheit skaliert. |

### Siehe auch

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


