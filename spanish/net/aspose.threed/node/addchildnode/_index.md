---
title: "Node.AddChildNode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Node. Añade un nodo hijo a este nodo"
type: docs
weight: 150
url: /es/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

Agregar un nodo hijo a este nodo

```csharp
public void AddChildNode(Node node)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo hijo que se adjuntará |

## Ejemplos

El siguiente código muestra cómo obtener todas las mallas de una escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//agrega un nuevo nodo manualmente
scene.RootNode.AddChildNode(newNode);
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


