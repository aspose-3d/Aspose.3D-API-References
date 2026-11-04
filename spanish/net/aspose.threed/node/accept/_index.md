---
title: "Node.Accept"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Node. Recorre todos los nodos descendientes, incluido el nodo actual, y llama al visitante con el nodo. El visitante puede interrumpir el recorrido devolviendo false"
type: docs
weight: 140
url: /es/net/aspose.threed/node/accept/
---
## Node.Accept method

Recorre todos los nodos descendientes (incluyendo el nodo actual) y llama al visitante con el nodo. El visitante puede interrumpir el recorrido devolviendo false

```csharp
public bool Accept(NodeVisitor visitor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| visitante | NodeVisitor | Función de devolución de llamada del visitante para visitar el nodo |

### Valor de retorno

true indica que el visitante ha interrumpido el recorrido.

## Ejemplos

El siguiente código muestra cómo obtener todas las mallas de una escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //continuar buscando
    return true;
});
```

### Ver también

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


