---
title: "Node.CreateChildNode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Erstellt einen untergeordneten Node."
type: docs
weight: 170
url: /de/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

Erstellt einen untergeordneten Node.

```csharp
public Node CreateChildNode()
```

### Rückgabewert

Der neue untergeordnete Node.

## Beispiele

Der folgende Code zeigt, wie man einen neuen Kindknoten unter dem Wurzelknoten erstellt.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen.

```csharp
public Node CreateChildNode(string nodeName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen untergeordneten Nodes |

### Rückgabewert

Der neue untergeordnete Node.

## Beispiele

Der folgende Code zeigt, wie man einen neuen Kindknoten unter dem Wurzelknoten erstellt.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

Erstellt einen neuen untergeordneten Node mit angehängter Entität.

```csharp
public Node CreateChildNode(Entity entity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Standard-Entität, die dem Node zugeordnet ist |

### Rückgabewert

Der neue untergeordnete Node.

## Beispiele

Der folgende Code zeigt, wie man einen neuen Kindknoten unter dem Wurzelknoten erstellt.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### Siehe auch

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen.

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen untergeordneten Nodes |
| Entität | Entität | Standard-Entität, die dem Node zugeordnet ist |

### Rückgabewert

Der neue untergeordnete Node.

### Siehe auch

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen und fügt die angegebene Entität sowie ein Material hinzu.

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen untergeordneten Nodes |
| Entität | Entität | Standard-Entität, die dem Node zugeordnet ist |
| Material | Material | Das dem Node zugeordnete Material |

### Rückgabewert

Der neue untergeordnete Node.

### Siehe auch

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


