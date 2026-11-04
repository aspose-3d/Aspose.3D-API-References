---
title: "Node.CreateChildNode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método del nodo. Crea un nodo hijo."
type: docs
weight: 170
url: /es/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

Crea un nodo hijo

```csharp
public Node CreateChildNode()
```

### Valor de retorno

El nuevo nodo hijo.

## Ejemplos

El siguiente código muestra cómo crear un nuevo nodo hijo bajo el nodo raíz.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

Crear un nuevo nodo hijo con el nombre de nodo dado

```csharp
public Node CreateChildNode(string nodeName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | String | El nombre del nuevo nodo hijo. |

### Valor de retorno

El nuevo nodo hijo.

## Ejemplos

El siguiente código muestra cómo crear un nuevo nodo hijo bajo el nodo raíz.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

Crear un nuevo nodo hijo con la entidad dada adjunta

```csharp
public Node CreateChildNode(Entity entity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |

### Valor de retorno

El nuevo nodo hijo.

## Ejemplos

El siguiente código muestra cómo crear un nuevo nodo hijo bajo el nodo raíz.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### Ver también

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

Crear un nuevo nodo hijo con el nombre de nodo dado

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | String | El nombre del nuevo nodo hijo. |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |

### Valor de retorno

El nuevo nodo hijo.

### Ver también

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

Crear un nuevo nodo hijo con el nombre de nodo dado, y adjuntar la entidad especificada y un material

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | String | El nombre del nuevo nodo hijo. |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |
| material | Material | El material adjunto al nodo |

### Valor de retorno

El nuevo nodo hijo.

### Ver también

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


