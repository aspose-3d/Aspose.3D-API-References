---
title: "Klasse PhongMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.PhongMaterial Klasse. Material für das Blinn-Phong-Shading-Modell"
type: docs
weight: 2570
url: /de/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Material für das Blinn-Phong-Schattierungsmodell.

```csharp
public class PhongMaterial : LambertMaterial
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Initialisiert eine neue Instanz der `PhongMaterial` Klasse. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Initialisiert eine neue Instanz der `PhongMaterial` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Liest oder setzt die Umgebungsfarbe |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Liest oder setzt die Diffusfarbe |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Liest oder setzt die Emissionsfarbe |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Liest oder setzt die Reflexionsfarbe. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Liest oder setzt die Dämpfung der Reflexionsfarbe. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Liest oder setzt den Glanzgrad, dieser steuert die Größe des spekularen Glanzpunkts. Die Formel für spekular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Liest oder setzt die spekularfarbe. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Liest oder setzt den spekularen Faktor. Die Formel für spekular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Liest oder setzt den Transparenzfaktor. Der Faktor sollte im Bereich zwischen 0 (0 %, vollständig undurchsichtig) und 1 (100 %, vollständig transparent) liegen. Jeder ungültige Faktorwert wird abgeschnitten. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Liest oder setzt die transparente Farbe. |

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

### Siehe auch

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


