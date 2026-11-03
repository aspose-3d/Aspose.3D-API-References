---
title: "Klasse Mesh"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.Mesh Klasse. Ein Mesh besteht aus vielen n-seitigen Polygonen"
type: docs
weight: 510
url: /de/net/aspose.threed.entities/mesh/
---
## Mesh class

Ein Mesh besteht aus vielen n-seitigen Polygonen.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Mesh](mesh/#constructor)() | Initialisiert eine neue Instanz der `Mesh` Klasse. |
| [Mesh](mesh/#constructor_4)(string) | Initialisiert eine neue Instanz der `Mesh` Klasse. |
| [Mesh](mesh/#constructor_1)(TextureData) | Erstelle ein Mesh mit einer angegebenen Höhenkarte; wenn das Pixelformat der Höhenkarte mehrere Komponenten enthält, wird die erste (üblicherweise die rote) Komponente als Höhenwert (z) verwendet. Die x- und y-Komponenten des Kontrollpunkts sind normalisierte Pixelkoordinaten. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | Erstelle ein Mesh mit einer angegebenen Höhenkarte; wenn das Pixelformat der Höhenkarte mehrere Komponenten enthält, wird die erste (üblicherweise die rote) Komponente als Höhenwert (z) verwendet. Die x- und y-Komponenten des Kontrollpunkts sind normalisierte Pixelkoordinaten. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | Erstelle ein Mesh mit einer angegebenen Höhenkarte; wenn das Pixelformat der Höhenkarte mehrere Komponenten enthält, wird die erste (üblicherweise die rote) Komponente als Höhenwert (z) verwendet. Die x- und y-Komponenten des Kontrollpunkts sind normalisierte Pixelkoordinaten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten werfen kann |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Liest alle Kontrollpunkte |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Liest alle Deformer, die mit dieser Geometrie verbunden sind. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Liest die Kanten des Mesh. Kanten sind optional im Mesh, daher kann es leer sein. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | Liest die Anzahl der Polygone. |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | Liest die Polygondefinition des Mesh. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Liest alle Vertex-Elemente. |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Liest oder setzt, ob die Geometrie sichtbar ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Fügt ein vorhandenes Vertex-Element zur aktuellen Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Erstellt ein [`VertexElementUV`](../vertexelementuv/) mit dem angegebenen Texturzuordnungstyp. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | Erstellt ein neues Polygon mit allen in *indices* definierten Scheitelpunkten. Um ein Polygon Scheitelpunkt für Scheitelpunkt zu erstellen, verwenden Sie bitte [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | Erstelle ein Polygon mit 3 Scheitelpunkten (Dreieck) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | Erstellt ein neues Polygon mit allen in *indices* definierten Scheitelpunkten. Um ein Polygon Scheitelpunkt für Scheitelpunkt zu erstellen, verwenden Sie bitte [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | Erstelle ein Polygon mit 4 Scheitelpunkten (Quad) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Ermittelt ein Scheitel-Element mit dem angegebenen Typ |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | Ermittelt den Enumerator für jedes innere Polygon. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | Ermittelt die Scheitelpunktanzahl des angegebenen Polygons. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Ermittelt eine [`VertexElementUV`](../vertexelementuv/) Instanz mit dem angegebenen Texturzuordnungstyp |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | Prüft, ob das aktuelle Mesh ein Mannigfaltigkeits-Mesh ist. Diese Funktion speichert das Ergebnis der Mannigfaltigkeitsberechnung nicht im Cache. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | Optimiert die Speichernutzung des Meshes, indem duplizierte Kontrollpunkte entfernt werden |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | Optimiert die Speichernutzung des Meshes, indem duplizierte Kontrollpunkte entfernt werden |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | Ermittelt die Mesh-Instanz der aktuellen Entität. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | Gibt ein trianguliertes Mesh zurück |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | Berechnet die Schnittmenge zweier Meshes |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | Berechnet die Vereinigung zweier Meshes |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | Berechnet die Differenz zweier Meshes |

## Beispiele

Um ein Polygon zum Mesh hinzuzufügen:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Durchlaufe alle Polygone im Mesh:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //Polygon verarbeiten
}
```

### Siehe auch

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


