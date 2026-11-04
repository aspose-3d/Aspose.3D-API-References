---
title: "Node.GetChild"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método de Node. Obtiene el nodo hijo en el índice especificado"
type: docs
weight: 200
url: /es/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

Obtiene el nodo hijo en el índice especificado.

```csharp
public Node GetChild(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | Int32 | Índice. |

### Valor de retorno

El hijo.

## Ejemplos

El siguiente código muestra cómo obtener un nodo hijo en el índice especificado.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

Obtiene el nodo hijo con el nombre especificado

```csharp
public Node GetChild(string nodeName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | String | El nombre del hijo a buscar. |

### Valor de retorno

El hijo.

## Ejemplos

El siguiente código muestra cómo obtener un nodo hijo con un nombre especificado

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


