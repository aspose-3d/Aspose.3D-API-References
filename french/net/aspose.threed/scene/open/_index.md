---
title: "Scene.Open"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Scene. Ouvre la scène à partir du flux donné en utilisant le format de fichier spécifié"
type: docs
weight: 140
url: /fr/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

Ouvre la scène à partir du flux fourni en utilisant le format de fichier spécifié.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
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

Le code suivant montre comment ouvrir une scène à partir d'un flux

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

Ouvre la scène à partir du flux fourni en utilisant la configuration d’E/S spécifiée.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
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

Le code suivant montre comment ouvrir une scène à partir d'un flux avec des options de chargement supplémentaires

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### Voir aussi

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

Ouvre la scène à partir du flux fourni

```csharp
public void Open(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un flux

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

Ouvre la scène à partir du flux fourni

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
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

Le code suivant montre comment ouvrir une scène à partir d'un flux avec un jeton d'annulation

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| format | FileFormat | Format de fichier. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un nom de fichier avec un jeton d'annulation

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié.

```csharp
public void Open(string fileName, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| options | LoadOptions | Configuration plus détaillée pour ouvrir le flux. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un nom de fichier avec des options de chargement supplémentaires

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### Voir aussi

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| options | LoadOptions | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un nom de fichier avec des options de chargement supplémentaires et un jeton d'annulation

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### Voir aussi

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

Ouvre la scène à partir du chemin fourni

```csharp
public void Open(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un nom de fichier

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

Ouvre la scène à partir du chemin fourni

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche de chargement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ImportException](../../importexception/) | Lancé lorsque l'entrée n'est pas un format 3D valide |

## Exemples

Le code suivant montre comment ouvrir une scène à partir d'un nom de fichier et d'une source de jeton d'annulation

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


