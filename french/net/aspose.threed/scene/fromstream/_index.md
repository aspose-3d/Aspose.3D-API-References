---
title: "Scene.FromStream"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Scene. Ouvre la scène à partir du flux donné en utilisant le format de fichier spécifié"
type: docs
weight: 30
url: /fr/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

Ouvre la scène à partir du flux fourni en utilisant le format de fichier spécifié.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| format | FileFormat | Format de fichier. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment créer une scène à partir d'un flux

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

Ouvre la scène à partir du flux fourni en utilisant la configuration d’E/S spécifiée.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| options | LoadOptions | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment créer une scène à partir d'un flux avec des options de chargement

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### Voir aussi

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

Ouvre la scène à partir du flux fourni

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment créer une scène à partir d'un flux avec une source de jeton d'annulation

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


