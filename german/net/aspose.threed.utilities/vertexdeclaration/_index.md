---
title: "Klasse VertexDeclaration"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.VertexDeclaration Klasse. Die Deklaration einer benutzerdefinierten Vertex-Struktur."
type: docs
weight: 2910
url: /de/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

Die Deklaration einer benutzerdefinierten Vertex-Struktur.

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Ermittelt die Anzahl aller Felder, die in dieser `VertexDeclaration` definiert sind. |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | Ein `VertexDeclaration` wird versiegelt, wenn es von [`TriMesh`](../../aspose.threed.entities/trimesh-1/) oder [`TriMesh`](../../aspose.threed.entities/trimesh/) verwendet wurde; weitere Änderungen sind nicht erlaubt. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | Die Größe der Vertex-Struktur in Byte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Erstelle ein `VertexDeclaration` basierend auf dem Layout einer [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Füge ein neues Vertex-Feld hinzu |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Alle Felder löschen. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Vergleicht diese Instanz mit einem angegebenen Objekt und gibt einen Hinweis auf deren relative Werte zurück. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein `VertexDeclaration`-Objekt sein muss, den gleichen Wert haben. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Gibt einen Enumerator zurück, um alle Vertex-Felder in dieser Instanz zu durchlaufen. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Gibt den Hash‑Code für diese Zeichenkette zurück. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | String-Darstellung von `VertexDeclaration` |

### Siehe auch

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


