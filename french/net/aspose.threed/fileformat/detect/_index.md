---
title: "FileFormat.Detect"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode FileFormat. Détecte le format du fichier à partir du flux de données; le nom du fichier est optionnel pour deviner les types qui n'ont pas d'en-tête magique"
type: docs
weight: 460
url: /fr/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

Détecter le format du fichier à partir du flux de données, le nom du fichier est optionnel pour deviner les types qui n'ont pas d'en-tête magique.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux contenant les données à détecter |
| fileName | String | Nom de fichier original des données, utilisé comme indice. |

### Valeur de retour

L'`[FileFormat](../)` instance du type détecté ou null si échec.

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Exception levée lors d'un échec de lecture des données. |

## Exemples

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### Voir aussi

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

Détecter le format du fichier à partir du nom du fichier, le fichier doit être lisible afin qu'Aspose.3D puisse détecter le format du fichier via l'en-tête du fichier.

```csharp
public static FileFormat Detect(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Chemin vers le fichier pour détecter le format du fichier. |

### Valeur de retour

L'`[FileFormat](../)` instance du type détecté ou null si échec.

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Exception levée lors d'un échec de lecture des données. |

## Exemples

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### Voir aussi

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


