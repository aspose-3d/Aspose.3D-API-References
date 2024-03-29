---
title: VertexDeclaration
second_title: Aspose.3D för .NET API-referens
description: Deklarationen av en egendefinierad vertexs struktur
type: docs
weight: 2670
url: /sv/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

Deklarationen av en egendefinierad vertexs struktur

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [VertexDeclaration](vertexdeclaration)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count) { get; } | Får räkningen av alla fält som definieras i detta[`VertexDeclaration`](../vertexdeclaration) |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed) { get; } | A[`VertexDeclaration`](../vertexdeclaration) kommer att förseglas när den har använts av[`TriMesh`](../../aspose.threed.entities/trimesh-1) eller[`TriMesh`](../../aspose.threed.entities/trimesh) , inga fler ändringar är tillåtna. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size) { get; } | Storleken i byte av vertexstrukturen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry)(Geometry, bool) | Skapa en[`VertexDeclaration`](../vertexdeclaration) baserat på a[`Geometry`](../../aspose.threed.entities/geometry) s layout. |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield)(VertexFieldDataType, VertexFieldSemantic, int, string) | Lägg till ett nytt vertexfält |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear)() | Rensa alla fält. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto)(VertexDeclaration) | Jämför denna instans med ett specificerat objekt och returnerar en indikation på deras relativa värden. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals)(object) | Bestämmer om denna instans och ett specificerat objekt, som också måste vara en[`VertexDeclaration`](../vertexdeclaration) objekt, har samma värde. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator)() | Får en uppräkning att gå igenom alla vertexfält i det här fallet. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode)() | Returnerar hashkoden för denna sträng. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring)() | Strängrepresentation av[`VertexDeclaration`](../vertexdeclaration) |

### Se även

* class [VertexField](../vertexfield)
* namnutrymme [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
