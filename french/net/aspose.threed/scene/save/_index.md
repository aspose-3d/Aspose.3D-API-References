---
title: "Scene.Save"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Scene. Enregistre la scène dans le flux en utilisant le format de fichier spécifié"
type: docs
weight: 160
url: /fr/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

```csharp
public void Save(Stream stream, FileFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| format | FileFormat | Format. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| format | FileFormat | Format. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche d'enregistrement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| options | SaveOptions | Configuration plus détaillée pour enregistrer le flux. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Voir aussi

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée, l'utilisateur est responsable de fermer le flux. |
| options | SaveOptions | Configuration plus détaillée pour enregistrer le flux. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche d'enregistrement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### Voir aussi

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié.

```csharp
public void Save(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié.

```csharp
public void Save(string fileName, FileFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| format | FileFormat | Format. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| format | FileFormat | Format. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche d'enregistrement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### Voir aussi

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié.

```csharp
public void Save(string fileName, SaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| options | SaveOptions | Configuration plus détaillée pour enregistrer le flux. |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### Voir aussi

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier. |
| options | SaveOptions | Configuration plus détaillée pour enregistrer le flux. |
| cancellationToken | CancellationToken | Jeton d'annulation pour la tâche d'enregistrement |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancé lorsqu'il échoue à lire l'entrée |
| [ExportException](../../exportexception/) | Lancée lorsqu'il échoue à exporter la scène vers le format 3D spécifié |

## Exemples

Le code suivant montre comment enregistrer la scène

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### Voir aussi

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


