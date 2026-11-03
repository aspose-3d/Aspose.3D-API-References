---
title: "Classe Material"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Shading.Material. Le matériau définit les paramètres nécessaires à l'apparence visuelle de la géométrie. Aspose.3D fournit des modèles d'éclairage pour LambertMaterial, PhongMaterial et ShaderMaterial."
type: docs
weight: 2540
url: /fr/net/aspose.threed.shading/material/
---
## Material class

Le matériau définit les paramètres nécessaires à l'apparence visuelle de la géométrie. Aspose.3D fournit des modèles d'éclairage pour [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) et [`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Obtient l'énumérateur pour énumérer les slots de texture internes. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Définit la texture au slot spécifié |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formate l'objet en chaîne |

## Champs

| Nom | Description |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | Utilisé dans [`SetTexture`](./settexture/) pour assigner une cartographie de texture ambiante. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | Utilisé dans [`SetTexture`](./settexture/) pour affecter un mappage de texture diffuse. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | Utilisé dans [`SetTexture`](./settexture/) pour affecter un mappage de texture émissive. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | Utilisé dans [`SetTexture`](./settexture/) pour affecter un mappage de texture normale. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | Utilisé dans [`SetTexture`](./settexture/) pour affecter un mappage de texture spéculaire. |

## Exemples

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

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


