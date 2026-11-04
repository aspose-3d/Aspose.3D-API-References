---
title: "Класс PbrSpecularMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.PbrSpecularMaterial. Материал для физически основанного рендеринга, основанный на диффузном цвете/спекулярности/блеске"
type: docs
weight: 2560
url: /ru/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Материал для физически основанного рендеринга, основанный на диффузном цвете/спекулярности/блеске

```csharp
public class PbrSpecularMaterial : Material
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | Конструктор `PbrSpecularMaterial` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | Получает или задает диффузный цвет материала, значение по умолчанию — (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | Получает или задает текстуру для диффузного отражения |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | Получает или задает эмиссионный цвет, значение по умолчанию — (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | Получает или задает текстуру для эмиссии |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | Получает или задает степень блеска (гладкости) материала, 1 означает полностью гладкий, а 0 — полностью шероховатый, значение по умолчанию — 1, диапазон [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | Получает или задает текстуру нормального отображения |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | Получает или задает зеркальный (спекулярный) цвет материала, значение по умолчанию — (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | Получает или задает текстуру для зеркального цвета, канал RGB хранит зеркальный цвет, а канал A — степень блеска. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение будет ограничено. |

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
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | Текстурная карта для зеркального блеска |

### См. также

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


