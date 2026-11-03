---
title: "Klasse SkinDeformer"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Deformers.SkinDeformer‑Klasse. Ein SkinDeformer enthält mehrere Knochen; jeder Knochen mischt einen Teil der Geometrie anhand von Gewichten der Kontrollpunkte."
type: docs
weight: 240
url: /de/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Ein SkinDeformer enthält mehrere Knochen, wobei jeder Knochen einen Teil der Geometrie anhand der Gewichte der Steuerpunkte mischt.

```csharp
public class SkinDeformer : Deformer
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | Initialisiert eine neue Instanz der `SkinDeformer`‑Klasse. |
| [SkinDeformer](skindeformer/#constructor_1)(string) | Initialisiert eine neue Instanz der `SkinDeformer`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | Gibt alle Knochen zurück, die der SkinDeformer enthält |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Gibt die Geometrie zurück, die diesen Deformer besitzt |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


