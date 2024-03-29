---
title: Line
second_title: Aspose.3D für .NET-API-Referenz
description: Eine Polylinie ist ein Pfad der durch eine Reihe von Punkten mit definiert wirdControlPoints./geometry/controlpoints  und verbunden durchSegments./line/segments  was bedeutet dass es sich auch um eine Menge verbundener Liniensegmente handeln kann. Die Linie ist normalerweise ein lineares Objekt was bedeutet dass sie nicht verwendet werden kann um eine Kurve darzustellen um eine Kurve darzustellen verwendetNurbsCurve./nurbscurve .
type: docs
weight: 420
url: /de/net/aspose.threed.entities/line/
---
## Line class

Eine Polylinie ist ein Pfad, der durch eine Reihe von Punkten mit definiert wird[`ControlPoints`](../geometry/controlpoints) , und verbunden durch[`Segments`](./segments) , was bedeutet, dass es sich auch um eine Menge verbundener Liniensegmente handeln kann. Die Linie ist normalerweise ein lineares Objekt, was bedeutet, dass sie nicht verwendet werden kann, um eine Kurve darzustellen, um eine Kurve darzustellen, verwendet[`NurbsCurve`](../nurbscurve) .

```csharp
public class Line : Curve
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Line](line#constructor)() | Initialisiert eine neue Instanz von[`Line`](../line) Klasse. |
| [Line](line#constructor_1)(string) | Initialisiert eine neue Instanz von[`Line`](../line) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints) { get; } | Ruft alle Kontrollpunkte ab |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ruft ab oder legt fest, ob diese Entität während des Exports ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ruft den ersten übergeordneten Knoten ab oder legt ihn fest. Wenn der erste übergeordnete Knoten festgelegt wird, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ruft alle übergeordneten Knoten ab, eine Entität kann an mehrere übergeordnete Knoten angehängt werden, um Geometrie zu instanziieren |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |
| [Segments](../../aspose.threed.entities/line/segments) { get; } | Ruft die Segmente der Linie ab |
| [Visible](../../aspose.threed.entities/line/visible) { get; set; } | Ruft ab oder legt fest, ob die Geometrie sichtbar ist |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints)(params Vector3[]) | Konstruiere a[`Line`](../line) Instanz aus einer Reihe von Punkten. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ruft den Begrenzungsrahmen des aktuellen Objekts in seinem Objektraum-Koordinatensystem ab. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Ruft den Schlüssel des Entity-Renderers ab, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices)() | Erzeuge die Folge 0,1,2,3....[`ControlPoints`](../geometry/controlpoints) .Länge-1 bis[`Segments`](./segments) damit die Kontrollpunkte als einzelne Linie verwendet werden können |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [Curve](../curve)
* namensraum [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
