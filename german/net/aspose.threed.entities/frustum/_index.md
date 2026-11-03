---
title: "Klasse Frustum"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Frustum Klasse. Die Basisklasse von Camera und Light"
type: docs
weight: 400
url: /de/net/aspose.threed.entities/frustum/
---
## Frustum class

Die Basisklasse von [`Camera`](../camera/) und [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Liest oder setzt das Seitenverhältnis des Frustums |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Liest oder setzt die Richtung, in die die Kamera blickt. Änderungen an dieser Eigenschaft wirken sich auch auf [`LookAt`](./lookat/) und [`Target`](./target/) aus. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Liest oder setzt die Entfernung der fernen Ebene des Frustums. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Liest oder setzt die interessierende Position, auf die die Kamera blickt. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Liest oder setzt die Entfernung der nahen Ebene des Frustums. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Liest oder setzt die Höhe, wenn das Frustum in orthografischer Projektion ist. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Liest oder setzt den Orientierungmodus des Frustums. Diese Eigenschaft funktioniert nur, wenn [`Target`](./target/) null ist. Ist der Wert FixedTarget, wird die Richtung stets über die Eigenschaft [`LookAt`](./lookat/) berechnet; andernfalls wird [`LookAt`](./lookat/) stets über [`Direction`](./direction/) berechnet. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Liest oder setzt das Ziel, auf das die Kamera blickt. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der [`LookAt`](./lookat/)-Eigenschaft liegen. |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Liest oder setzt die Aufwärtsrichtung der Kamera |

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
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


