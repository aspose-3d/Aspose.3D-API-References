---
title: "Класс Material"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.Material. Material определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модели освещения для LambertMaterial, PhongMaterial и ShaderMaterial."
type: docs
weight: 2540
url: /ru/net/aspose.threed.shading/material/
---
## Material class

Material определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модели освещения для [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) и [`ShaderMaterial`](../shadermaterial/).

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Получает перечислитель для перечисления внутренних слотов текстур. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Получает текстуру из указанного слота; это может быть имя свойства материала или имя параметра шейдера. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Устанавливает текстуру в указанный слот |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Преобразует объект в строку |

## Поля

| Имя | Описание |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | Используется в [`SetTexture`](./settexture/) для назначения амбиентного текстурного отображения. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | Используется в [`SetTexture`](./settexture/) для назначения диффузного отображения текстуры. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | Используется в [`SetTexture`](./settexture/) для назначения эмиссивного отображения текстуры. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | Используется в [`SetTexture`](./settexture/) для назначения нормального отображения текстуры. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | Используется в [`SetTexture`](./settexture/) для назначения спекулярного отображения текстуры. |

## Примеры

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

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


