---
title: "Klasse PbrSpecularMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.PbrSpecularMaterial Klasse. Material für physikalisch basiertes Rendering basierend auf Diffusfarbe/Specular/Glanz"
type: docs
weight: 2560
url: /de/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material für physikalisch basiertes Rendering basierend auf Diffusfarbe/Specular/Glanz.

```csharp
public class PbrSpecularMaterial : Material
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | Konstruktor von `PbrSpecularMaterial` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | Liest oder setzt die Diffusfarbe des Materials, Standardwert ist (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | Liest oder setzt die Textur für Diffus |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | Liest oder setzt die Emissionsfarbe, Standardwert ist (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | Liest oder setzt die Textur für Emission |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | Liest oder setzt den Glanz (Glätte) des Materials, 1 bedeutet vollkommen glatt und 0 bedeutet vollkommen rau, Standardwert ist 1, Bereich ist [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | Liest oder setzt die Textur für Normal Mapping |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | Liest oder setzt die Specularfarbe des Materials, Standardwert ist (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | Liest oder setzt die Textur für Specularfarbe, Kanal RGB speichert die Specularfarbe und Kanal A speichert den Glanz. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | Liest oder setzt den Transparenzfaktor. Der Faktor sollte im Bereich zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird abgeschnitten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Liefert den Enumerator, um interne Textur‑Slots zu enumerieren. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Liefert die Textur aus dem angegebenen Slot, es kann der Name einer Material‑Eigenschaft oder ein Shader‑Parametername sein. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Setzt die Textur in den angegebenen Slot. |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formatiert das Objekt zu einer Zeichenkette. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | Die Texturkarte für Specularglanz |

### Siehe auch

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


