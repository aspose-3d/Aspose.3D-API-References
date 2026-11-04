---
title: "Класс ShaderMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.ShaderMaterial. Шейдерный материал позволяет описать материал с помощью внешнего движка рендеринга или языка шейдеров. ShaderMaterial использует ShaderTechnique для описания конкретных деталей рендеринга, и будет использован наиболее подходящий вариант в зависимости от конечной платформы рендеринга. Например, ваш экземпляр ShaderMaterial может иметь две техники: одна определена в HLSL, другая — в GLSL. На платформе без окна следует использовать GLSL вместо HLSL."
type: docs
weight: 2580
url: /ru/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Шейдерный материал позволяет описать материал с помощью внешнего движка рендеринга или языка шейдеров. `ShaderMaterial` использует [`ShaderTechnique`](../shadertechnique/) для описания конкретных деталей рендеринга, и будет выбран наиболее подходящий вариант в зависимости от конечной платформы рендеринга. Например, ваш экземпляр `ShaderMaterial` может иметь две техники: одна определена в HLSL, а другая — в GLSL. На платформе без окна следует использовать GLSL вместо HLSL.

```csharp
public class ShaderMaterial : Material
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | Инициализирует новый экземпляр класса `ShaderMaterial`. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | Инициализирует новый экземпляр класса `ShaderMaterial`. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | Получает все доступные техники, определённые в этом материале. |

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


