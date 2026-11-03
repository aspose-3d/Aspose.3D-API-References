---
title: "Node.SelectSingleObject"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Sélectionne un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath"
type: docs
weight: 240
url: /fr/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

Sélectionner un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath.

```csharp
public object SelectSingleObject(string path)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| path | String | La requête de type XPath |

### Valeur de retour

Objet situé par la requête de type XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | ParseException sera levée si le chemin contient une requête malformée. |

## Exemples

Sélectionner un seul nœud en utilisant une expression de type XPath

```csharp
//Créer une scène pour les tests
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//Sélectionner un seul objet caméra sous les nœuds enfants du nœud nommé 'c' sous le nœud racine
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// Sélectionner le nœud nommé 'a1' sous le nœud racine, même si le 'a1' n'est pas un nœud enfant direct du
var obj = s.RootNode.SelectSingleObject("a1");
//Sélectionner le nœud lui-même, puisque le '/' est sélectionné directement sur le nœud racine, ainsi le nœud racine est sélectionné.
obj = s.RootNode.SelectSingleObject("/");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


