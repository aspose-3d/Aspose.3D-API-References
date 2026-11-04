---
title: "Класс PbrMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.PbrMaterial. Материал для физически основанного рендеринга на основе цвета альбедо/металличности/шероховатости"
type: docs
weight: 2550
url: /ru/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости

```csharp
public class PbrMaterial : Material
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | Создать экземпляр PBR-материала по умолчанию |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | Создать PBR-материал по умолчанию с указанным значением цвета альбедо. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | Получает или задает базовый цвет материала |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | Получает или задает текстуру альбедо |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | Получает или задает эмиссионный цвет |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | Получает или задает текстуру для эмиссии |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | Получает или задает металлическость материала, значение 1 означает, что материал является металлом, а значение 0 — диэлектриком. |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | Получает или задает текстуру для металлическости (в канале R) и шероховатости (в канале G) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | Получает или задает текстуру нормального отображения |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | Получает или задает коэффициент окклюзии окружающего света |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | Получает или задает текстуру окклюзии окружающего света |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | Получает или задает шероховатость материала, значение 1 означает полностью шероховатый материал, а значение 0 — полностью гладкий. |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | Получает или задает текстуру спекулярного цвета |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение будет ограничено. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | Разрешить преобразование другого материала в PbrMaterial |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Получает перечислитель для перечисления внутренних слотов текстур. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Получает текстуру из указанного слота; это может быть имя свойства материала или имя параметра шейдера. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Устанавливает текстуру в указанный слот |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Преобразует объект в строку |

### См. также

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


