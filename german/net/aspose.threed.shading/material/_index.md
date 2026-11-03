---
title: "Klasse Material"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.Material Klasse. Material definiert die Parameter, die für das visuelle Erscheinungsbild von Geometrie notwendig sind. Aspose.3D bietet Shading-Modelle für LambertMaterial, PhongMaterial und ShaderMaterial"
type: docs
weight: 2540
url: /de/net/aspose.threed.shading/material/
---
## Material class

Material definiert die Parameter, die für das visuelle Erscheinungsbild von Geometrie notwendig sind. Aspose.3D bietet Shading-Modelle für [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) und [`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

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
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | Wird in [`SetTexture`](./settexture/) verwendet, um eine Umgebungs-Texturzuordnung zuzuweisen. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | Wird in [`SetTexture`](./settexture/) verwendet, um eine diffuse Texturzuordnung zuzuweisen. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | Wird in [`SetTexture`](./settexture/) verwendet, um eine emittierende Texturzuordnung zuzuweisen. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | Wird in [`SetTexture`](./settexture/) verwendet, um eine Normalen-Texturzuordnung zuzuweisen. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | Wird in [`SetTexture`](./settexture/) verwendet, um eine spekulare Texturzuordnung zuzuweisen. |

## Beispiele

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


