---
title: "Klasse PbrMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.PbrMaterial Klasse. Material für physikalisch basiertes Rendering basierend auf Albedo-Farbe/Metallisch/Rauheit"
type: docs
weight: 2550
url: /de/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

Material für physikalisch basiertes Rendering basierend auf Albedo-Farbe/Metallisch/Rauheit.

```csharp
public class PbrMaterial : Material
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | Erstelle eine Standard-PBR-Materialinstanz |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | Erstelle ein Standard-PBR-Material mit angegebenem Albedo-Farbwert. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | Liest oder setzt die Basisfarbe des Materials |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | Liest oder setzt die Textur für Albedo |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | Liest oder setzt die Emissionsfarbe |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | Liest oder setzt die Textur für Emission |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | Liest oder setzt den Metallanteil des Materials, ein Wert von 1 bedeutet, dass das Material ein Metall ist, und ein Wert von 0 bedeutet, dass das Material ein Dielektrikum ist. |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | Liest oder setzt die Textur für Metallisch (im R-Kanal) und Rauheit (im G-Kanal) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | Liest oder setzt die Textur für Normal Mapping |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | Liest oder setzt den Faktor der Umgebungsokklusion |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | Liest oder setzt die Textur für die Umgebungsokklusion |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | Liest oder setzt die Rauheit des Materials, ein Wert von 1 bedeutet, dass das Material vollständig rau ist, und ein Wert von 0 bedeutet, dass das Material vollständig glatt ist. |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | Liest oder setzt die Textur für die spekulare Farbe |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | Liest oder setzt den Transparenzfaktor. Der Faktor sollte im Bereich zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird abgeschnitten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | Ermöglicht die Konvertierung anderer Materialien in PbrMaterial |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Liefert den Enumerator, um interne Textur‑Slots zu enumerieren. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Liefert die Textur aus dem angegebenen Slot, es kann der Name einer Material‑Eigenschaft oder ein Shader‑Parametername sein. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Setzt die Textur in den angegebenen Slot. |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formatiert das Objekt zu einer Zeichenkette. |

### Siehe auch

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


