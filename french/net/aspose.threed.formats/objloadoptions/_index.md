---
title: "Classe ObjLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.ObjLoadOptions. Options de chargement pour le obj wavefront"
type: docs
weight: 1360
url: /fr/net/aspose.threed.formats/objloadoptions/
---
## ObjLoadOptions class

Options de chargement pour wavefront obj

```csharp
public class ObjLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ObjLoadOptions](objloadoptions/)() | Constructeur de `ObjLoadOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnableMaterials](../../aspose.threed.formats/objloadoptions/enablematerials/) { get; set; } | Obtient ou définit si les matériaux sont importés pour chaque objet |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objloadoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit si le système de coordonnées des points de contrôle/normal doit être inversé lors de l'importation. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [NormalizeNormal](../../aspose.threed.formats/objloadoptions/normalizenormal/) { get; set; } | Obtient ou définit si le vecteur normal doit être normalisé pendant le chargement. La valeur par défaut est true. |
| [Scale](../../aspose.threed.formats/objloadoptions/scale/) { get; set; } | Échelles sur les axes x/y/z, la valeur par défaut est 1.0 |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


