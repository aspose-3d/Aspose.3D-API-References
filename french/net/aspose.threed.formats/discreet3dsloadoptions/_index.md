---
title: "Classe Discreet3dsLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.Discreet3dsLoadOptions. Options de chargement pour le fichier 3DS"
type: docs
weight: 1120
url: /fr/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Options de chargement pour le fichier 3DS.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | Constructeur de `Discreet3dsLoadOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | Obtient ou définit si la transformation définie dans la première image de la piste d'animation doit être utilisée. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Le définir sur true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


