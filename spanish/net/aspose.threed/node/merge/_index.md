---
title: "Node.Merge"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Node. Desacopla todo lo que está bajo el nodo y lo adjunta al nodo actual"
type: docs
weight: 220
url: /es/net/aspose.threed/node/merge/
---
## Node.Merge method

Desvincular todo bajo el nodo y adjuntarlo al nodo actual.

```csharp
public void Merge(Node node)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo |  |

## Ejemplos

El siguiente código muestra cómo combinar dos archivos 3D en un solo archivo

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


