---
title: Material
second_title: Aspose.3D für .NET-API-Referenz
description: Material definiert die Parameter die für das visuelle Erscheinungsbild der Geometrie erforderlich sind. Aspose.3D bietet ein Schattierungsmodell fürLambertMaterial./lambertmaterial PhongMaterial./phongmaterial undShaderMaterial./shadermaterial
type: docs
weight: 2290
url: /de/net/aspose.threed.shading/material/
---
## Material class

Material definiert die Parameter, die für das visuelle Erscheinungsbild der Geometrie erforderlich sind. Aspose.3D bietet ein Schattierungsmodell für[`LambertMaterial`](../lambertmaterial) ,[`PhongMaterial`](../phongmaterial) und[`ShaderMaterial`](../shadermaterial)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Ruft den Enumerator ab, um interne Texturslots aufzuzählen. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Ruft die Textur aus dem angegebenen Slot ab, es kann der Eigenschaftsname des Materials oder der Parametername des Shaders sein |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Setzt die Textur auf den angegebenen Slot |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Formatiert Objekt in string |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient) | Verwendet in[`SetTexture`](./settexture) um ein Umgebungstextur-Mapping zuzuweisen. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse) | Verwendet in[`SetTexture`](./settexture) um ein diffuses Textur-Mapping zuzuweisen. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive) | Verwendet in[`SetTexture`](./settexture) um ein emittierendes Textur-Mapping zuzuweisen. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal) | Verwendet in[`SetTexture`](./settexture) um ein normales Textur-Mapping zuzuweisen. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular) | Verwendet in[`SetTexture`](./settexture) um ein spiegelndes Textur-Mapping zuzuweisen. |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject)
* class [TextureSlot](../textureslot)
* namensraum [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->