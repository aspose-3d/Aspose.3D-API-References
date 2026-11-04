---
title: "Node.Excluded"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Node. Obtiene o establece si excluir este nodo y todos los nodos/hijos o entidades durante la exportación"
type: docs
weight: 60
url: /es/net/aspose.threed/node/excluded/
---
## Node.Excluded property

Obtiene o establece si excluir este nodo y todos los nodos/entidades hijos durante la exportación.

```csharp
public bool Excluded { get; set; }
```

## Ejemplos

El siguiente código muestra cómo excluir el nodo especificado de la exportación

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


