---
title: "Klasse ShaderMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.ShaderMaterial Klasse. Ein Shader-Material ermöglicht es, das Material durch eine externe Rendering-Engine oder Shadersprache zu beschreiben. ShaderMaterial verwendet ShaderTechnique, um die konkreten Rendering-Details zu beschreiben, und das am besten geeignete wird je nach Ziel-Rendering-Plattform verwendet. Beispielsweise kann Ihre ShaderMaterial-Instanz zwei Techniken haben, eine definiert durch HLSL und eine andere durch GLSL. Unter Nicht‑Window‑Plattform sollte GLSL anstelle von HLSL verwendet werden."
type: docs
weight: 2580
url: /de/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Ein Shader-Material ermöglicht es, das Material durch eine externe Rendering-Engine oder Shadersprache zu beschreiben. `ShaderMaterial` verwendet [`ShaderTechnique`](../shadertechnique/), um die konkreten Rendering-Details zu beschreiben, und das am besten geeignete wird je nach Ziel-Rendering-Plattform verwendet. Beispielsweise kann Ihre `ShaderMaterial`-Instanz zwei Techniken haben, eine definiert durch HLSL und eine andere definiert durch GLSL. Unter Nicht‑Window‑Plattform sollte GLSL anstelle von HLSL verwendet werden.

```csharp
public class ShaderMaterial : Material
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | Initialisiert eine neue Instanz der `ShaderMaterial`-Klasse. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | Initialisiert eine neue Instanz der `ShaderMaterial`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | Ruft alle verfügbaren Techniken ab, die in diesem Material definiert sind. |

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

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


