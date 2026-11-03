---
title: "Node.CreateChildNode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Crée un nœud enfant."
type: docs
weight: 170
url: /fr/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

Crée un nœud enfant

```csharp
public Node CreateChildNode()
```

### Valeur de retour

Le nouveau nœud enfant.

## Exemples

Le code suivant montre comment créer un nouveau nœud enfant sous le nœud racine.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

Créer un nouveau nœud enfant avec le nom de nœud donné

```csharp
public Node CreateChildNode(string nodeName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |

### Valeur de retour

Le nouveau nœud enfant.

## Exemples

Le code suivant montre comment créer un nouveau nœud enfant sous le nœud racine.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

Créer un nouveau nœud enfant avec l'entité donnée attachée

```csharp
public Node CreateChildNode(Entity entity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | Entité par défaut attachée au node |

### Valeur de retour

Le nouveau nœud enfant.

## Exemples

Le code suivant montre comment créer un nouveau nœud enfant sous le nœud racine.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### Voir aussi

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

Créer un nouveau nœud enfant avec le nom de nœud donné

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |
| entité | Entité | Entité par défaut attachée au node |

### Valeur de retour

Le nouveau nœud enfant.

### Voir aussi

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

Créer un nouveau nœud enfant avec le nom de nœud donné, et attacher l'entité spécifiée ainsi qu'un matériau

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |
| entité | Entité | Entité par défaut attachée au node |
| matériau | Matériau | Le matériau attaché au node |

### Valeur de retour

Le nouveau nœud enfant.

### Voir aussi

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


