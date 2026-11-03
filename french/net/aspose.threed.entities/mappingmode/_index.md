---
title: "Enum MappingMode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.MappingMode enum. Détermine comment l'élément est mappé sur une surface. Le MappingMode définit comment VertexElement est mappé sur la surface de la géométrie"
type: docs
weight: 500
url: /fr/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

Détermine comment l'élément est mappé sur une surface. Le `MappingMode` définit comment [`VertexElement`](../vertexelement/) est mappé sur la surface de la géométrie.

```csharp
public enum MappingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ControlPoint | `0` | Chaque donnée est mappée au point de contrôle de la géométrie. |
| PolygonVertex | `1` | Les données sont mappées au sommet du polygone. Lorsqu'un point de contrôle est partagé par plusieurs polygones et que les données sont mappées en tant que PolygonVertex, le même point de contrôle en tant que sommet de polygone différent aura ses propres données. |
| Polygon | `2` | Les données sont mappées au polygone. Chaque sommet de polygone partage les mêmes données lorsque le mode de mappage est Polygon. |
| Edge | `3` | Les données sont mappées à l'arête. Chaque extrémité d'arête partage les mêmes données lorsque le mode de mappage est Edge. |
| AllSame | `4` | Une donnée est mappée à toute la surface. Quelle que soit l'interprétation des données comme point de contrôle/sommet de polygone/extremités d'arête, les données sont toujours les mêmes, comme défini par AllSame. |

### Voir aussi

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


