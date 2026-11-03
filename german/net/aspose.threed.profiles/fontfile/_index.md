---
title: "Klasse FontFile"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Profiles.FontFile Klasse. Fontdatei enthält Definitionen für Glyphen und wird verwendet, um Textprofile zu erstellen."
type: docs
weight: 1720
url: /de/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Fontdatei enthält Definitionen für Glyphen, die zum Erstellen von Textprofilen verwendet werden.

```csharp
public abstract class FontFile : A3DObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Lade FontFile aus Dateinamen |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Parse FontFile aus Bytes |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

## Beispiele

Der folgende Code zeigt, wie man ein 3D‑Mesh aus Text mit einer angegebenen Schriftdatei erstellt.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


