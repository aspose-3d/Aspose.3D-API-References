---
title: "PdfFormat.Extract"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PdfFormat. Extrait le contenu 3D brut du fichier PDF"
type: docs
weight: 10
url: /fr/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

Extraire le contenu 3D brut du fichier PDF.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier du PDF d'entrée |
| mot de passe | Byte[] | Mot de passe du fichier PDF |

### Valeur de retour

Une liste de tous les contenus 3D en octets, incluant les formats que Aspose.3D ne prend pas en charge.

## Exemples

Le code suivant montre comment extraire tout le contenu 3D brut d'un fichier PDF 3D et les écrire dans des fichiers.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Voir aussi

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

Extraire le contenu 3D brut du flux PDF.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux du fichier PDF d'entrée |
| mot de passe | Byte[] | Mot de passe du fichier PDF |

### Valeur de retour

Une liste de tous les contenus 3D en octets, incluant les formats que Aspose.3D ne prend pas en charge.

## Exemples

Le code suivant montre comment extraire tout le contenu 3D brut d'un fichier PDF 3D et les écrire dans des fichiers.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Voir aussi

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


