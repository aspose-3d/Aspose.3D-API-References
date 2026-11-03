---
title: "FileFormat.GetFormatByExtension"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileFormat-Methode. Gibt das bevorzugte Dateiformat anhand des Dateierweiterungsnamens zurück. Der Erweiterungsname sollte mit einem Punkt beginnen."
type: docs
weight: 470
url: /de/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

Ermittelt das bevorzugte Dateiformat aus dem Dateierweiterungsnamen. Der Erweiterungsname sollte mit einem Punkt ('.') beginnen.

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extensionName | String | Der Erweiterungsname beginnt mit '.' für die Abfrage. |

### Rückgabewert

Instanz von [`FileFormat`](../), andernfalls wird null zurückgegeben.

## Beispiele

Der folgende Code zeigt, wie man eine Szene mit dem angegebenen Format im Speicher speichert.

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### Siehe auch

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


