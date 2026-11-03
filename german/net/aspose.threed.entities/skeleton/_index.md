---
title: "Klasse Skeleton"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Skeleton Klasse. Das Skeleton wird hauptsächlich von CAD‑Software verwendet, um dem Designer zu helfen, die Transformation der Skelettstruktur zu manipulieren; es ist normalerweise außerhalb der CAD‑Software nutzlos. Damit die Skelett‑Hierarchie wie ein Objekt in CAD‑Software wirkt, muss der oberste Skeleton‑Knoten als Wurzel markiert werden, indem der Typ auf Skeleton gesetzt wird und alle Kinder auf Bone gesetzt werden."
type: docs
weight: 710
url: /de/net/aspose.threed.entities/skeleton/
---
## Skeleton class

Das `Skeleton` wird hauptsächlich von CAD‑Software verwendet, um dem Designer zu helfen, die Transformation der Skelettstruktur zu manipulieren; es ist normalerweise außerhalb der CAD‑Software nutzlos. Damit die Skelett‑Hierarchie wie ein Objekt in CAD‑Software wirkt, muss der oberste `Skeleton`‑Knoten als Wurzel markiert werden, indem [`Type`](./type/) auf Skeleton gesetzt wird und alle Kinder auf Bone gesetzt werden.

```csharp
public class Skeleton : Entity
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Initialisiert eine neue Instanz der `Skeleton`‑Klasse. |
| [Skeleton](skeleton/#constructor_1)(string) | Initialisiert eine neue Instanz der `Skeleton`‑Klasse. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Initialisiert eine neue Instanz der `Skeleton`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Liest oder setzt die Größe des Gliedknotens, die in CAD‑Software verwendet wird, um die Größe des Knochens darzustellen. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Liest oder setzt den Typ des Skeletts. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


