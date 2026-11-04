---
title: "Класс PhongMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.PhongMaterial. Материал для модели освещения Blinn-Phong."
type: docs
weight: 2570
url: /ru/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Материал для модели затенения Блинна-Фонга.

```csharp
public class PhongMaterial : LambertMaterial
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Инициализирует новый экземпляр класса `PhongMaterial`. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Инициализирует новый экземпляр класса `PhongMaterial`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Получает или задает цвет окружающего света |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Получает или задает диффузный цвет |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Получает или задает эмиссионный цвет |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Получает или задает цвет отражения. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Получает или задает затухание цвета отражения. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Получает или задает степень блеска, это контролирует размер зеркального отражения. Формула зеркального отражения: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Получает или задает зеркальный (спекулярный) цвет. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Получает или задает коэффициент зеркального отражения. Формула зеркального отражения: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение будет ограничено. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Получает или задает прозрачный цвет. |

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

### См. также

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


