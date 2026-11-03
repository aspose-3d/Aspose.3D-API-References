---
title: "Klasse Patch"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Patch class. Ein Patch ist eine parametrische Modellierungsfläche, ähnlich wie NurbsSurface, sie ist auch durch zwei PatchDirection, U und V, definiert. Der Unterschied zwischen Patch und NurbsSurface besteht darin, dass die PatchDirection-Kurve eine von Bezier, QuadraticBezier, BasisSpline, CardinalSpline und Linear sein kann."
type: docs
weight: 560
url: /de/net/aspose.threed.entities/patch/
---
## Patch class

Ein `Patch` ist eine parametrische Modellierungsfläche, ähnlich wie [`NurbsSurface`](../nurbssurface/), sie ist auch durch zwei [`PatchDirection`](../patchdirection/) definiert, das [`U`](./u/) und das [`V`](./v/). Der Unterschied zwischen `Patch` und [`NurbsSurface`](../nurbssurface/) besteht darin, dass die [`PatchDirection`](../patchdirection/)‑Kurve eine von Bezier, QuadraticBezier, BasisSpline, CardinalSpline und Linear sein kann.

```csharp
public class Patch : Geometry
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Patch](patch/#constructor)() | Initialisiert eine neue Instanz der `Patch`‑Klasse. |
| [Patch](patch/#constructor_1)(string) | Initialisiert eine neue Instanz der `Patch`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Liest alle Kontrollpunkte |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Liest alle Deformer, die mit dieser Geometrie verbunden sind. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [U](../../aspose.threed.entities/patch/u/) { get; } | Liefert die u‑Richtung. |
| [V](../../aspose.threed.entities/patch/v/) { get; } | Liefert die v‑Richtung. |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Liest alle Vertex-Elemente. |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Liest oder setzt, ob die Geometrie sichtbar ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Fügt ein vorhandenes Vertex-Element zur aktuellen Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Ermittelt ein Scheitel-Element mit dem angegebenen Typ |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Ermittelt eine [`VertexElementUV`](../vertexelementuv/) Instanz mit dem angegebenen Texturzuordnungstyp |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


