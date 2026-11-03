---
title: "Scene.FromFile"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Scene. Ouvre la scène depuis le chemin donné en utilisant le format de fichier spécifié"
type: docs
weight: 20
url: /fr/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

Le code suivant montre comment créer une scène à partir d'un fichier

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

Le code suivant montre comment créer une scène à partir d'un fichier

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### Voir aussi

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

Ouvre la scène à partir du chemin fourni

```csharp
public static Scene FromFile(string fileName)
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

Le code suivant montre comment créer une scène à partir d'un fichier

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

Ouvre la scène à partir du chemin fourni

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

Le code suivant montre comment créer une scène à partir d'un fichier

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


