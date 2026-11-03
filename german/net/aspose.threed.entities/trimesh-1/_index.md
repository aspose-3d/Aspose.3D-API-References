---
title: "Klasse TriMeshT"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.TriMesh1T Klasse. Generische Version von TriMesh für vom Benutzer statisch definierten Vertex-Typ"
type: docs
weight: 800
url: /de/net/aspose.threed.entities/trimesh-1/
---
## TriMesh&lt;T&gt; class

Generische Version von [`TriMesh`](../trimesh/) für den vom Benutzer statisch definierten Vertex-Typ

```csharp
public class TriMesh<T> : TriMesh
    where T : struct
```

| Parameter | Beschreibung |
| --- | --- |
| T |  |

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TriMesh](trimesh/)(string) | Initialisiere eine Instanz von [`TriMesh`](../trimesh/) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | Die Kapazität der vorab zugewiesenen Scheitelpunkte. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Liest oder setzt, ob diese Entität beim Exportieren ausgeschlossen werden soll. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | Die Anzahl der Indizes in diesem [`TriMesh`](../trimesh/) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Liest oder setzt den ersten übergeordneten Knoten; wird der erste übergeordnete Knoten gesetzt, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Liest alle übergeordneten Knoten, eine Entität kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | Die Anzahl der nicht zusammengeführten Vertices, die von [`BeginVertex`](../trimesh/beginvertex/) und [`EndVertex`](../trimesh/endvertex/) übergeben wurden. |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | Das Vertex-Layout des [`TriMesh`](../trimesh/). |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | Die Anzahl der Vertices in diesem [`TriMesh`](../trimesh/) |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | Die Gesamtgröße aller Scheitelpunkte in Bytes |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromMesh](../../aspose.threed.entities/trimesh-1/frommesh/)(Mesh) | Erstelle ein TriMesh aus dem angegebenen Mesh-Objekt mit automatisch generiertem Vertex-Layout. |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | Füge ein neues Dreieck hinzu |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | Beginne mit dem Hinzufügen eines Scheitelpunkts |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | Beende das Hinzufügen eines Scheitelpunkts |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ermittelt den Schlüssel des Entity-Renderers, der im Renderer registriert ist |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | Hole den Enumerator, um [`Vertex`](../../aspose.threed.utilities/vertex/) zu enumerieren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | Lade Scheitelpunkte aus Bytes, die Länge der Bytes muss ein ganzzahliges Vielfaches der Scheitelpunktgröße sein. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | Lese das double-Feld |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | Lese das float-Feld |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | Lese das vector2-Feld |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | Lese das vector3-Feld |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | Lese das vector4-Feld |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | Lese das vector2-Feld |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | Lese das vector3-Feld |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | Lese das vector4-Feld |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | Gibt die Zeichenkettenrepräsentation von [`TriMesh`](../trimesh/) zurück |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | Konvertiere die Scheitelpunktdaten in ein Byte-Array |
| [VerticesToTypedArray](../../aspose.threed.entities/trimesh-1/verticestotypedarray/)() | Konvertiere die Vertex-Daten in ein typisiertes Array |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | Schreibe die Indexdaten als 16‑Bit‑Integer in den Stream |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | Schreibe die Indexdaten als 32‑Bit‑Integer in den Stream |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | Schreibe die Scheitelpunktdaten in den angegebenen Stream |

### Siehe auch

* class [TriMesh](../trimesh/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


