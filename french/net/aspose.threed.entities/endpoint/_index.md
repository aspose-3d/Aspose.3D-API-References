---
title: EndPoint
second_title: Référence de l'API Aspose.3D pour .NET
description: Le point final pour couper la courbe peut être une valeur de paramètre ou un point cartésien.
type: docs
weight: 340
url: /fr/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

Le point final pour couper la courbe, peut être une valeur de paramètre ou un point cartésien.

```csharp
public struct EndPoint
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EndPoint](endpoint#constructor_1)(double) | Construire un[`EndPoint`](../endpoint) à partir d'un paramètre réel. |
| [EndPoint](endpoint#constructor)(Vector3) | Construire un[`EndPoint`](../endpoint) à partir d'un point cartésien. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint) { get; } | Obtient le point final en tant que point cartésien, ou lève une exception. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue) { get; } | Obtient le point final en tant que paramètre réel ou lève une exception. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint) { get; } | Le point final est-il un point cartésien ? |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree)(double) | Créer un point final mesuré en degrés. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian)(double) | Créer un point final mesuré en radian. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring)() | Renvoie une représentation sous forme de chaîne du point de fin actuel. |

### Voir également

* espace de noms [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->