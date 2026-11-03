---
title: "Klasse Light"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Light Klasse. Das Licht beleuchtet die Szene"
type: docs
weight: 460
url: /de/net/aspose.threed.entities/light/
---
## Light class

Das Licht beleuchtet die Szene.

Die Formel zur Berechnung der Gesamtdämpfung des Lichts lautet: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Light](light/#constructor)() | Initialisiert eine neue Instanz der `Light` Klasse. |
| [Light](light/#constructor_1)(string) | Initialisiert eine neue Instanz der `Light` Klasse. |
| [Light](light/#constructor_2)(string, LightType) | Initialisiert eine neue Instanz der `Light` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Liest oder setzt das Seitenverhältnis des Frustums |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | Liest oder setzt, ob die aktuelle Lichtinstanz andere Objekte beleuchten kann. |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | Liest oder setzt, ob das Licht Schatten auf andere Objekte werfen kann. |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | Liest oder setzt die Farbe des Lichts |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | Liest oder setzt die konstante Dämpfung zur Berechnung der Gesamtdämpfung des Lichts |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Liest oder setzt die Richtung, in die die Kamera blickt. Änderungen an dieser Eigenschaft wirken sich auch auf [`LookAt`](../frustum/lookat/) und [`Target`](../frustum/target/) aus. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | Liest oder setzt den Abfallkegelwinkel (in Grad). |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Liest oder setzt die Entfernung der fernen Ebene des Frustums. |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | Liest oder setzt den Hot-Spot-Kegelwinkel (in Grad). |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | Liest oder setzt die Intensität des Lichts, Standardwert ist 100 |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | Liest oder setzt den Typ des Lichts |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | Liest oder setzt die lineare Dämpfung zur Berechnung der Gesamtdämpfung des Lichts |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Liest oder setzt die interessierende Position, auf die die Kamera blickt. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Liest oder setzt die Entfernung der nahen Ebene des Frustums. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Liest oder setzt die Höhe, wenn das Frustum in orthografischer Projektion ist. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | Liest oder setzt die quadratische Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Liest oder setzt den Orientierungsmodus des Sichtvolumens. Diese Eigenschaft funktioniert nur, wenn [`Target`](../frustum/target/) null ist. Wenn der Wert FixedTarget ist, wird die Richtung immer über die Eigenschaft [`LookAt`](../frustum/lookat/) berechnet. Andernfalls wird [`LookAt`](../frustum/lookat/) immer über [`Direction`](../frustum/direction/) berechnet. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | Liest oder setzt die Farbe des Schattens. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Liest oder setzt das Ziel, auf das die Kamera schaut. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der [`LookAt`](../frustum/lookat/) Eigenschaft liegen. |
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

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


