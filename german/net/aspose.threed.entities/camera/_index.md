---
title: "Klasse Camera"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Camera Klasse. Die Kamera beschreibt den Blickpunkt des Betrachters, der die Szene ansieht."
type: docs
weight: 300
url: /de/net/aspose.threed.entities/camera/
---
## Camera class

Die Kamera beschreibt den Blickpunkt des Betrachters, der die Szene betrachtet.

```csharp
public class Camera : Frustum
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Camera](camera/#constructor)() | Initialisiert eine neue Instanz der `Camera`-Klasse. |
| [Camera](camera/#constructor_1)(ProjectionType) | Initialisiert eine neue Instanz der `Camera`-Klasse. |
| [Camera](camera/#constructor_2)(string) | Initialisiert eine neue Instanz der `Camera`-Klasse. |
| [Camera](camera/#constructor_3)(string, ProjectionType) | Initialisiert eine neue Instanz der `Camera`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | Liest oder setzt den Blendenmodus der Kamera |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Liest oder setzt das Seitenverhältnis des Frustums |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | Liest oder setzt das Seitenverhältnis der Ansichtsebene. |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Liest oder setzt die Richtung, in die die Kamera blickt. Änderungen an dieser Eigenschaft wirken sich auch auf [`LookAt`](../frustum/lookat/) und [`Target`](../frustum/target/) aus. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Liest oder setzt die Entfernung der fernen Ebene des Frustums. |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | Liest oder setzt das Sichtfeld der Kamera in Grad; diese Eigenschaft wird nur verwendet, wenn ApertureMode Horizontal oder Vertikal ist. |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | Liest oder setzt das horizontale Sichtfeld der Kamera in Grad; diese Eigenschaft wird nur verwendet, wenn ApertureMode HorizAndVert ist. |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | Ruft das vertikale Sichtfeld der Kamera in Grad ab oder legt es fest, diese Eigenschaft wird nur verwendet, wenn ApertureMode HorizAndVert ist. |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | Ruft die Höhe der Ansichtsebene in Zoll ab oder legt sie fest. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Liest oder setzt die interessierende Position, auf die die Kamera blickt. |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | Ruft die Vergrößerung der orthografischen Kamera ab oder legt sie fest. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Liest oder setzt die Entfernung der nahen Ebene des Frustums. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Liest oder setzt die Höhe, wenn das Frustum in orthografischer Projektion ist. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | Ruft den Projektionstyp der Kamera ab oder legt ihn fest. Standardmäßig wird die perspektivische Projektion verwendet. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Liest oder setzt den Orientierungsmodus des Sichtvolumens. Diese Eigenschaft funktioniert nur, wenn [`Target`](../frustum/target/) null ist. Wenn der Wert FixedTarget ist, wird die Richtung immer über die Eigenschaft [`LookAt`](../frustum/lookat/) berechnet. Andernfalls wird [`LookAt`](../frustum/lookat/) immer über [`Direction`](../frustum/direction/) berechnet. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Liest oder setzt das Ziel, auf das die Kamera schaut. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der [`LookAt`](../frustum/lookat/) Eigenschaft liegen. |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Liest oder setzt die Aufwärtsrichtung der Kamera |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | Ruft die Breite der Ansichtsebene in Zoll ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | Bewegt die Kamera nach vorne in Richtung ihrer Ausrichtung oder ihres Ziels. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


