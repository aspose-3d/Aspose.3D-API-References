---
title: "Classe GltfSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.GltfSaveOptions. Options d'enregistrement pour le format glTF"
type: docs
weight: 1280
url: /fr/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Options d'enregistrement pour le format glTF.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | Constructeur de `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | Constructeur de `GltfSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | Appliquer [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) au maillage. La valeur par défaut est false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Ceci est ignoré lors de l'exportation glTF en mode binaire. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | Obtient ou définit si la compression draco doit être activée |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | Intégrez tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | Utilisez un encodeur draco externe pour accélérer la vitesse de compression draco. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de la valeur originale pour contourner la validation. La valeur par défaut est (0, 1, 0). |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | Inversez le composant v(t) des coordonnées de texture, la valeur par défaut est true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | Le glTF standard ne prend en charge que les formats PNG/JPG comme textures, cette option indique comment Aspose.3D convertit les images non standard vers un format pris en charge lors de l'exportation. La valeur par défaut est Png. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | Convertisseur personnalisé pour transformer le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas attribué, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. Cette propriété est utilisée lors de l'exportation d'une scène vers un fichier glTF 2.0. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false. |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | Enregistrez les propriétés dynamiques des objets de la scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | Sérialisez les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. Mettre cela à false entraînera l'exportation par Aspose.3D d'un ensemble de shaders vertex/fragment si ExportShaders. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


