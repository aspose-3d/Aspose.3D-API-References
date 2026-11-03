---
title: "Klasse Bone"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Deformers.Bone‑Klasse. Ein Bone definiert die Teilmenge der Kontrollpunkte einer Geometrie und legt das Blend‑Gewicht für jeden Kontrollpunkt fest. Das Bone‑Objekt kann nicht direkt verwendet werden; eine SkinDeformer‑Instanz wird verwendet, um die Geometrie zu deformieren, und SkinDeformer enthält einen Satz von Bones, wobei jeder Bone mit einem Knoten verknüpft ist. HINWEIS: Ein Kontrollpunkt einer Geometrie kann an mehr als einem Bone gebunden sein."
type: docs
weight: 190
url: /de/net/aspose.threed.deformers/bone/
---
## Bone class

Ein Bone definiert die Teilmenge der Kontrollpunkte einer Geometrie und legt das Blend‑Gewicht für jeden Kontrollpunkt fest. Das `Bone`‑Objekt kann nicht direkt verwendet werden, eine [`SkinDeformer`](../skindeformer/)‑Instanz wird verwendet, um die Geometrie zu deformieren, und [`SkinDeformer`](../skindeformer/) enthält einen Satz von Bones, wobei jeder Bone mit einem Knoten verknüpft ist. HINWEIS: Ein Kontrollpunkt einer Geometrie kann an mehr als einem Bone gebunden sein.

```csharp
public class Bone : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Bone](bone/#constructor)() | Initialisiert eine neue Instanz der `Bone`‑Klasse. |
| [Bone](bone/#constructor_1)(string) | Initialisiert eine neue Instanz der `Bone`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | Liest oder setzt die Transformationsmatrix des Bones. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | Der Verknüpfungsmodus eines Knochens bezieht sich auf die Art und Weise, wie ein Knochen mit seinem übergeordneten Knochen innerhalb einer hierarchischen Struktur verbunden oder verknüpft ist. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | Liest oder setzt den Knoten. Der Bone‑Knoten ist der Bone, an dem das Skin befestigt ist; der [`SkinDeformer`](../skindeformer/) verwendet den Bone‑Knoten, um die Verschiebung der Kontrollpunkte zu beeinflussen. Der Bone‑Knoten hat normalerweise ein angehängtes [`Skeleton`](../../aspose.threed.entities/skeleton/), dies ist jedoch nicht zwingend erforderlich. Das angehängte [`Skeleton`](../../aspose.threed.entities/skeleton/) wird üblicherweise von DCC‑Software verwendet, um dem Benutzer das Skelett anzuzeigen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | Liest oder setzt die Transformationsmatrix des Knotens, der den Bone enthält. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | Ermittelt die Anzahl der Gewichte, dies wird automatisch durch [`SetWeight`](./setweight/) erweitert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | Ermittelt das Gewicht für den Kontrollpunkt, der durch den Index angegeben wird. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | Setzt das Gewicht für den Kontrollpunkt, der durch den Index angegeben wird. |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


