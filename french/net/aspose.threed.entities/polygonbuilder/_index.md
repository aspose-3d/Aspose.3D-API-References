---
title: "Classe PolygonBuilder"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.PolygonBuilder. Une classe d'aide pour créer des polygones pour Mesh."
type: docs
weight: 610
url: /fr/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Une classe d'aide pour créer des polygones pour [`Mesh`](../mesh/).

```csharp
public sealed class PolygonBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Initialise une nouvelle instance de la classe `PolygonBuilder`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Ajoute un indice de sommet au polygone. |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Commence à ajouter un nouveau polygone. |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Termine la création du polygone. |

## Exemples

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Égal à :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Si tous les indices sont prêts à être utilisés, [`CreatePolygon`](../mesh/createpolygon/) est préférable, sinon `PolygonBuilder` serait un meilleur choix.

### Voir aussi

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


