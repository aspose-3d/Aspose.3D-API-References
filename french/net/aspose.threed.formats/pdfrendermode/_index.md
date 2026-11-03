---
title: "Enum PdfRenderMode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Enum Aspose.ThreeD.Formats.PdfRenderMode. Le mode de rendu spécifie le style dans lequel l'œuvre 3D est rendue"
type: docs
weight: 1410
url: /fr/net/aspose.threed.formats/pdfrendermode/
---
## PdfRenderMode enumeration

Le mode de rendu spécifie le style dans lequel l'œuvre 3D est rendue.

```csharp
public enum PdfRenderMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Solid | `0` | Affiche des formes géométriques texturées et éclairées. |
| SolidWireframe | `1` | Affiche des formes géométriques texturées et éclairées (triangles) avec des arêtes d’une seule couleur au-dessus. |
| Transparent | `2` | Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau supplémentaire de transparence. |
| TransparentWireframe | `3` | Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau supplémentaire de transparence, avec des arêtes opaques d’une seule couleur au-dessus. |
| BoundingBox | `4` | Affiche les arêtes de la boîte englobante de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud. |
| TransparentBoundingBox | `5` | Affiche les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau supplémentaire de transparence. |
| TransparentBoundingBoxOutline | `6` | Affiche les arêtes et les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau supplémentaire de transparence. |
| Wireframe | `7` | Affiche uniquement les arêtes d’une seule couleur. |
| ShadedWireframe | `8` | Affiche uniquement les arêtes, tout en interpolant leur couleur entre leurs deux sommets et en appliquant l’éclairage. |
| HiddenWireframe | `9` | Affiche les arêtes d’une seule couleur, tout en supprimant les arêtes orientées vers l’arrière et les arêtes occultées. |
| Vertices | `10` | Affiche uniquement les sommets d’une seule couleur. |
| ShadedVertices | `11` | Affiche uniquement les sommets, tout en utilisant leur couleur de sommet et en appliquant l’éclairage. |
| Illustration | `12` | Affiche les arêtes de silhouette avec les surfaces, supprime les lignes occultées. |
| SolidOutline | `13` | Affiche les arêtes de silhouette avec des surfaces éclairées et texturées, supprime les lignes occultées. |
| ShadedIllustration | `14` | Affiche les arêtes de silhouette avec des surfaces éclairées et texturées ainsi qu’un terme émissif supplémentaire pour éliminer les zones mal éclairées de l’œuvre. |

### Voir aussi

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


