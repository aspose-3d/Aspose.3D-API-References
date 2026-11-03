---
title: "Klasse PointCloud"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.PointCloud Klasse. Die Punktwolke enthält keine Topologieinformationen, sondern nur die Kontrollpunkte und die Vertex-Elemente."
type: docs
weight: 600
url: /de/net/aspose.threed.entities/pointcloud/
---
## PointCloud class

Die Punktwolke enthält keine Topologieinformationen, sondern nur die Kontrollpunkte und die Vertex-Elemente.

```csharp
public class PointCloud : Geometry
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PointCloud](pointcloud/#constructor)() | Konstruktor von `PointCloud` |
| [PointCloud](pointcloud/#constructor_1)(string) | Konstruktor von `PointCloud` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Liest alle Kontrollpunkte |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Liest alle Deformer, die mit dieser Geometrie verbunden sind. |
| [Dimension](../../aspose.threed.entities/pointcloud/dimension/) { get; set; } | Wenn ein Dimensionswert für die Punktwolke vorhanden ist, weist dies auf eine organisierte Punktwolke hin. Ohne angegebene Größe wird sie als unorganisierte Punktwolke betrachtet. Eine organisierte Punktwolke bedeutet, dass sie eine bildähnliche Struktur hat. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Liest alle Vertex-Elemente. |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Liest oder setzt, ob die Geometrie sichtbar ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry)(Geometry) | Erstelle eine neue PointCloud‑Instanz aus einem Geometrieobjekt |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry_1)(Geometry, int) | Erstellen Sie eine neue Punktwolkeninstanz aus einem Geometrieobjekt. Dichte ist die Anzahl der Punkte pro Einheitstriangle (Einheitstriangle ist das Dreieck mit der maximalen Oberfläche aus dem Mesh). |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Fügt ein vorhandenes Vertex-Element zur aktuellen Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Ermittelt ein Scheitel-Element mit dem angegebenen Typ |
| override [GetEntityRendererKey](../../aspose.threed.entities/pointcloud/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Ermittelt eine [`VertexElementUV`](../vertexelementuv/) Instanz mit dem angegebenen Texturzuordnungstyp |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


