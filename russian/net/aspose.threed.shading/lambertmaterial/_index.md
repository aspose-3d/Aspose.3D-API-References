---
title: "Класс LambertMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.LambertMaterial. Материал для модели ламбертового затенения."
type: docs
weight: 2530
url: /ru/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

Материал для модели затенения Ламберта

```csharp
public class LambertMaterial : Material
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LambertMaterial](lambertmaterial/#constructor)() | Инициализирует новый экземпляр класса `LambertMaterial`. |
| [LambertMaterial](lambertmaterial/#constructor_1)(string) | Инициализирует новый экземпляр класса `LambertMaterial`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Получает или задает цвет окружающего света |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Получает или задает диффузный цвет |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Получает или задает эмиссионный цвет |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
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

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


