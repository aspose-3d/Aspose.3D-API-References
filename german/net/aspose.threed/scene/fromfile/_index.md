---
title: "Scene.FromFile"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Methode. Öffnet die Szene vom angegebenen Pfad mit dem angegebenen Dateiformat."
type: docs
weight: 20
url: /de/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Format | FileFormat | Dateiformat. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einer Datei erstellt.

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | LoadOptions | Detailliertere Konfiguration zum Öffnen des Streams. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einer Datei erstellt.

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### Siehe auch

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

Öffnet die Szene vom angegebenen Pfad.

```csharp
public static Scene FromFile(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einer Datei erstellt.

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

Öffnet die Szene vom angegebenen Pfad.

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einer Datei erstellt.

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


