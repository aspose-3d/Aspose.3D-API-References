---
title: "Node.SelectObjects"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Sélectionne plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath."
type: docs
weight: 230
url: /fr/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

Sélectionner plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath.

```csharp
public List<object> SelectObjects(string path)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| path | String | La requête de type XPath |

### Valeur de retour

Plusieurs objets correspondent à la requête de type XPath.

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
//Sélectionner les objets dont le type est Camera ou dont le nom est 'light', quel que soit leur emplacement.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


