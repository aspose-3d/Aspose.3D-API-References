---
title: "BoundingBox.op_Multiply"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BoundingBox. Surcharge d'opérateur pour multiplier, les nouveaux coins minimum et maximum de la boîte englobante seront transformés par la matrice"
type: docs
weight: 170
url: /fr/net/aspose.threed.utilities/boundingbox/op_multiply/
---
## BoundingBox Multiply operator

Surcharge d'opérateur pour la multiplication, les coins minimum et maximum de la nouvelle boîte englobante seront transformés par la matrice.

```csharp
public static BoundingBox operator *(BoundingBox bbox, Matrix4 mat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bbox | BoundingBox | La boîte englobante d'entrée. |
| mat | Matrix4 | La matrice utilisée pour transformer les coins de la boîte englobante |

### Valeur de retour

Le produit de la boîte englobante et de la matrice de transformation.

### Voir aussi

* struct [Matrix4](../../matrix4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


