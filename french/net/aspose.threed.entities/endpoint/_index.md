---
title: "Structure EndPoint"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Structure Aspose.ThreeD.Entities.EndPoint. Le point final pour tronquer la courbe peut être une valeur de paramètre ou un point cartésien"
type: docs
weight: 390
url: /fr/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

Le point final pour tronquer la courbe peut être une valeur de paramètre ou un point cartésien.

```csharp
public struct EndPoint
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EndPoint](endpoint/#constructor_1)(double) | Construire un `EndPoint` à partir d'un paramètre réel. |
| [EndPoint](endpoint/#constructor)(Vector3) | Construire un `EndPoint` à partir d'un point cartésien. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint/) { get; } | Obtient le point final en tant que point cartésien, ou lance une exception. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue/) { get; } | Obtient le point final en tant que paramètre réel, ou lance une exception. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint/) { get; } | Le point final est-il un point cartésien ? |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree/)(double) | Créer un point final mesuré en degrés. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian/)(double) | Créer un point final mesuré en radians. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring/)() | Renvoie une représentation sous forme de chaîne du point final actuel. |

### Voir aussi

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


