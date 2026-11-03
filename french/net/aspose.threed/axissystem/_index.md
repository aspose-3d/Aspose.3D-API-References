---
title: "Classe AxisSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.AxisSystem. Le système d'axes est une combinaison du vecteur up du système de coordonnées et du vecteur front."
type: docs
weight: 150
url: /fr/net/aspose.threed/axissystem/
---
## AxisSystem class

Le système d'axes est une combinaison du système de coordonnées, du vecteur ascendant et du vecteur avant.

```csharp
public class AxisSystem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | Construit un nouveau système d'axes |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | Construit un nouveau système d'axes |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | Obtient le système de coordonnées de ce système d'axes. |
| [Front](../../aspose.threed/axissystem/front/) { get; } | Obtient le vecteur front de ce système d'axes |
| [Up](../../aspose.threed/axissystem/up/) { get; } | Obtient le vecteur up de ce système d'axes. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | Créer `AxisSystem` à partir de [`AssetInfo`](../assetinfo/) |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | Créer une matrice utilisée pour convertir du système d'axes actuel vers le système d'axes cible. |

### Voir aussi

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


