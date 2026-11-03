---
title: "Scene.Open"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Methode. Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats"
type: docs
weight: 140
url: /de/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
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

Der folgende Code zeigt, wie man eine Szene aus einem Stream öffnet

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

Öffnet die Szene aus dem angegebenen Stream unter Verwendung der angegebenen IO-Konfiguration.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
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

Der folgende Code zeigt, wie man eine Szene aus einem Stream mit zusätzlichen Ladeoptionen öffnet

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### Siehe auch

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

Öffnet die Szene aus dem angegebenen Stream.

```csharp
public void Open(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einem Stream öffnet

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

Öffnet die Szene aus dem angegebenen Stream.

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
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

Der folgende Code zeigt, wie man eine Szene aus einem Stream mit einem Abbruch-Token öffnet

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
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

Der folgende Code zeigt, wie man eine Szene aus einem Dateinamen mit einem Abbruch-Token öffnet

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Open(string fileName, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | LoadOptions | Detailliertere Konfiguration zum Öffnen des Streams. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ImportException](../../importexception/) | Wird ausgelöst, wenn die Eingabe kein gültiges 3D-Format ist |

## Beispiele

Der folgende Code zeigt, wie man eine Szene aus einem Dateinamen mit zusätzlichen Ladeoptionen öffnet

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### Siehe auch

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
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

Der folgende Code zeigt, wie man eine Szene aus einem Dateinamen mit zusätzlichen Ladeoptionen und einem Abbruch-Token öffnet

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### Siehe auch

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

Öffnet die Szene vom angegebenen Pfad.

```csharp
public void Open(string fileName)
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

Der folgende Code zeigt, wie man eine Szene aus einem Dateinamen öffnet

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

Öffnet die Szene vom angegebenen Pfad.

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
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

Der folgende Code zeigt, wie man eine Szene aus einem Dateinamen und einer Abbruch-Token-Quelle öffnet

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


