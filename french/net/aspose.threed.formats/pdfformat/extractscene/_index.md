---
title: "PdfFormat.ExtractScene"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PdfFormat. Extraire des scènes 3D d'un fichier PDF"
type: docs
weight: 20
url: /fr/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

Extraire les scènes 3D du fichier PDF.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier du PDF d'entrée |

### Valeur de retour

Liste des scènes 3D décodées prises en charge par Aspose.3D

## Exemples

Le code suivant montre comment extraire toutes les scènes 3D prises en charge d'un fichier PDF 3D, et les écrire au format obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

Extraire les scènes 3D du fichier PDF.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier du PDF d'entrée |
| mot de passe | Byte[] | Mot de passe du fichier PDF |

### Valeur de retour

Liste des scènes 3D décodées prises en charge par Aspose.3D

## Exemples

Le code suivant montre comment extraire toutes les scènes 3D prises en charge d'un fichier PDF 3D, et les écrire au format obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

Extraire le contenu 3D brut du flux PDF.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux du fichier PDF d'entrée |
| mot de passe | Byte[] | Mot de passe du fichier PDF |

### Valeur de retour

Liste des scènes 3D décodées prises en charge par Aspose.3D

## Exemples

Le code suivant montre comment extraire toutes les scènes 3D prises en charge d'un fichier PDF 3D, et les écrire au format obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


