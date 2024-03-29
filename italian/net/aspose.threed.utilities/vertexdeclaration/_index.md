---
title: VertexDeclaration
second_title: Riferimento API Aspose.3D per .NET
description: La dichiarazione della struttura di un vertice definito dallutente
type: docs
weight: 2670
url: /it/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

La dichiarazione della struttura di un vertice definito dall'utente

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VertexDeclaration](vertexdeclaration)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count) { get; } | Ottiene il conteggio di tutti i campi definiti in questo[`VertexDeclaration`](../vertexdeclaration) |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed) { get; } | A[`VertexDeclaration`](../vertexdeclaration) sarà sigillato quando è stato utilizzato da[`TriMesh`](../../aspose.threed.entities/trimesh-1) o[`TriMesh`](../../aspose.threed.entities/trimesh) , non sono consentite altre modifiche. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size) { get; } | La dimensione in byte della struttura del vertice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry)(Geometry, bool) | Crea un[`VertexDeclaration`](../vertexdeclaration) basato su a[`Geometry`](../../aspose.threed.entities/geometry) s layout. |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield)(VertexFieldDataType, VertexFieldSemantic, int, string) | Aggiungi un nuovo campo vertice |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear)() | Cancella tutti i campi. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto)(VertexDeclaration) | Confronta questa istanza con un oggetto specificato e restituisce un'indicazione dei relativi valori. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals)(object) | Determina se questa istanza e un oggetto specificato, che deve essere anche a[`VertexDeclaration`](../vertexdeclaration) oggetto, hanno lo stesso valore. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator)() | Ottiene un enumeratore per scorrere tutti i campi di vertice in questa istanza. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode)() | Restituisce il codice hash per questa stringa. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring)() | Rappresentazione in stringa di[`VertexDeclaration`](../vertexdeclaration) |

### Guarda anche

* class [VertexField](../vertexfield)
* spazio dei nomi [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
