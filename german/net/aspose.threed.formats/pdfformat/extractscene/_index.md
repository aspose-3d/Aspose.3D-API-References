---
title: "PdfFormat.ExtractScene"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PdfFormat-Methode. Extrahiert 3D-Szenen aus einer PDF-Datei"
type: docs
weight: 20
url: /de/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

3D-Szenen aus PDF-Datei extrahieren.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname der Eingabe-PDF-Datei |

### Rückgabewert

Liste der dekodierten 3D-Szenen, die von Aspose.3D unterstützt werden

## Beispiele

Der folgende Code zeigt, wie man alle unterstützten 3D-Szenen aus einer 3D-PDF-Datei extrahiert und sie im OBJ-Format speichert.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

3D-Szenen aus PDF-Datei extrahieren.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname der Eingabe-PDF-Datei |
| Passwort | Byte[] | Passwort der PDF-Datei |

### Rückgabewert

Liste der dekodierten 3D-Szenen, die von Aspose.3D unterstützt werden

## Beispiele

Der folgende Code zeigt, wie man alle unterstützten 3D-Szenen aus einer 3D-PDF-Datei extrahiert und sie im OBJ-Format speichert.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

Roh-3D-Inhalt aus PDF-Stream extrahieren.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Stream der Eingabe-PDF-Datei |
| Passwort | Byte[] | Passwort der PDF-Datei |

### Rückgabewert

Liste der dekodierten 3D-Szenen, die von Aspose.3D unterstützt werden

## Beispiele

Der folgende Code zeigt, wie man alle unterstützten 3D-Szenen aus einer 3D-PDF-Datei extrahiert und sie im OBJ-Format speichert.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


