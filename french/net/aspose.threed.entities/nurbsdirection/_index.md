---
title: "Classe NurbsDirection"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.NurbsDirection. Une NurbsSurface 3D possède deux directions, U et V ; le NurbsDirection définit les données pour chaque direction. Une direction est en fait une courbe NURBS, ce qui signifie qu'elle est également définie par son Order, ses KnotVectors et un ensemble de points de contrôle pondérés définis dans NurbsSurface."
type: docs
weight: 530
url: /fr/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

Une 3D [`NurbsSurface`](../nurbssurface/) possède deux directions, le [`U`](../nurbssurface/u/) et le [`V`](../nurbssurface/v/), le `NurbsDirection` définit les données pour chaque direction. Une direction est en fait une courbe NURBS, ce qui signifie qu'elle est également définie par son [`Order`](./order/), un [`KnotVectors`](./knotvectors/), et un ensemble de points de contrôle pondérés (définis dans [`NurbsSurface`](../nurbssurface/)).

```csharp
public class NurbsDirection
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NurbsDirection](nurbsdirection/)() | Construire une nouvelle instance de `NurbsDirection` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count/) { get; set; } | Obtient ou définit le nombre de points de contrôle dans la direction actuelle. |
| [Degree](../../aspose.threed.entities/nurbsdirection/degree/) { get; set; } | Obtient ou définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions/) { get; set; } | Obtient ou définit le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle. |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors/) { get; } | Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity/) { get; } | Obtient la multiplicité. |
| [Order](../../aspose.threed.entities/nurbsdirection/order/) { get; set; } | Obtient ou définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe. |
| [Type](../../aspose.threed.entities/nurbsdirection/type/) { get; set; } | Obtient ou définit le type de la direction actuelle. |

### Voir aussi

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


