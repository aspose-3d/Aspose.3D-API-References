---
title: "Classe Html5SaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.Html5SaveOptions. Options d'enregistrement pour HTML5"
type: docs
weight: 1290
url: /fr/net/aspose.threed.formats/html5saveoptions/
---
## Html5SaveOptions class

Options d'enregistrement pour HTML5

```csharp
public class Html5SaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Html5SaveOptions](html5saveoptions/)() | Constructeur de `Html5SaveOptions` avec tous les paramètres par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CameraPosition](../../aspose.threed.formats/html5saveoptions/cameraposition/) { get; set; } | Obtient ou définit la position initiale de la caméra, la valeur par défaut est (10, 10, 10) |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FarPlane](../../aspose.threed.formats/html5saveoptions/farplane/) { get; set; } | Obtient ou définit le plan lointain de la caméra, la valeur par défaut est 1000. |
| [FieldOfView](../../aspose.threed.formats/html5saveoptions/fieldofview/) { get; set; } | Obtient ou définit le champ de vision, la valeur par défaut est 45, mesurée en degrés. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookAt](../../aspose.threed.formats/html5saveoptions/lookat/) { get; set; } | Obtient ou définit la position de regard par défaut, la valeur par défaut est (0, 0, 0) |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [NearPlane](../../aspose.threed.formats/html5saveoptions/nearplane/) { get; set; } | Obtient ou définit le plan proche de la caméra, la valeur par défaut est 1 |
| [OrientationBox](../../aspose.threed.formats/html5saveoptions/orientationbox/) { get; set; } | Afficher une boîte d'orientation. La valeur par défaut est vraie. |
| [ShowGrid](../../aspose.threed.formats/html5saveoptions/showgrid/) { get; set; } | Afficher une grille dans la scène. La valeur par défaut est vraie. |
| [ShowRulers](../../aspose.threed.formats/html5saveoptions/showrulers/) { get; set; } | Afficher des règles des axes x/y/z dans la scène pour mesurer le modèle. La valeur par défaut est fausse. |
| [ShowUI](../../aspose.threed.formats/html5saveoptions/showui/) { get; set; } | Afficher une interface simple dans la scène. La valeur par défaut est vraie. |
| [UpVector](../../aspose.threed.formats/html5saveoptions/upvector/) { get; set; } | Obtient ou définit le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y" |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


