---
title: TrimmedCurve
second_title: Référence de l'API Aspose.3D pour .NET
description: Une courbe bornée qui a coupé la courbe de base aux deux extrémités.
type: docs
weight: 750
url: /fr/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

Une courbe bornée qui a coupé la courbe de base aux deux extrémités.

```csharp
public class TrimmedCurve : Curve
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TrimmedCurve](trimmedcurve)() | Constructeur de[`TrimmedCurve`](../trimmedcurve) |

## Propriétés

| Nom | La description |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve) { get; set; } | La courbe de base à ajuster. |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Obtient ou définit s'il faut exclure cette entité lors de l'exportation. |
| [First](../../aspose.threed.entities/trimmedcurve/first) { get; set; } | Le premier point final à ajuster peut être un point cartésien ou un paramètre réel. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Obtient ou définit le premier nœud parent, si défini le premier nœud parent, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de la géométrie |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtient la collection de toutes les propriétés. |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection) { get; set; } | Obtient ou définit si le résultat ajusté utilise la même direction que la courbe de base. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Second](../../aspose.threed.entities/trimmedcurve/second) { get; set; } | Le deuxième point final à ajuster peut être un point cartésien ou un paramètre réel. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trouve la propriété. Il peut s'agir d'une propriété dynamique (créée par CreateDynamicProperty/SetProperty) ou d'une propriété native (identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées de l'espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Obtient la clé du rendu d'entité enregistré dans le rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Supprimer la propriété spécifiée identifiée par name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir également

* class [Curve](../curve)
* espace de noms [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
