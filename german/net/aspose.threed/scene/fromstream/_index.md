---
title: "Scene.FromStream"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Methode. Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats"
type: docs
weight: 30
url: /de/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| Format | FileFormat | Dateiformat. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einem Stream erstellt

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

Öffnet die Szene aus dem angegebenen Stream unter Verwendung der angegebenen IO-Konfiguration.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| options | LoadOptions | Detailliertere Konfiguration zum Öffnen des Streams. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einem Stream mit Ladeoptionen erstellt

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### Siehe auch

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

Öffnet die Szene aus dem angegebenen Stream.

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| cancellationToken | CancellationToken | Abbruch-Token für den Ladevorgang |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einem Stream mit einer Abbruch-Token-Quelle erstellt

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


