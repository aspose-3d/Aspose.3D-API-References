---
title: "Classe IOConfig"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.IOConfig. Configuration d'E/S pour la sérialisation/désérialisation. L'utilisateur peut spécifier des configurations détaillées comme le chemin de recherche des dépendances ou les configurations liées au format ici."
type: docs
weight: 1300
url: /fr/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

Configuration d'E/S pour la sérialisation/désérialisation. L'utilisateur peut spécifier des configurations détaillées comme le chemin de recherche des dépendances ou les configurations liées au format ici.

```csharp
public class IOConfig
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | Obtient ou définit la classe de fabrique pour le système de fichiers. La fabrique par défaut créera LocalFileSystem, qui n’est pas adaptée à un environnement serveur. |

### Voir aussi

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


