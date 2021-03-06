---
title: ShaderMaterial
second_title: Справочник по Aspose.3D для .NET API
description: Материал шейдера позволяет описывать материал с помощью внешнего механизма рендеринга или языка шейдера. ShaderMaterial./shadermaterialиспользуетShaderTechnique./shadertechniqueдля описания конкретных деталей рендеринга и наиболее подходящий будет использоваться в соответствии с конечной платформой рендеринга. Например ваш экземплярShaderMaterial./shadermaterialможет иметь два метода один определяется HLSL а другой определяется GLSL Под не-Window платформой следует использовать GLSL вместо HLSL
type: docs
weight: 2330
url: /ru/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Материал шейдера позволяет описывать материал с помощью внешнего механизма рендеринга или языка шейдера. [`ShaderMaterial`](../shadermaterial)использует[`ShaderTechnique`](../shadertechnique)для описания конкретных деталей рендеринга и наиболее подходящий будет использоваться в соответствии с конечной платформой рендеринга. Например, ваш экземпляр[`ShaderMaterial`](../shadermaterial)может иметь два метода, один определяется HLSL, а другой определяется GLSL Под не-Window платформой следует использовать GLSL вместо HLSL

```csharp
public class ShaderMaterial : Material
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ShaderMaterial](shadermaterial#constructor)() | Инициализирует новый экземпляр класса[`ShaderMaterial`](../shadermaterial). |
| [ShaderMaterial](shadermaterial#constructor_1)(string) | Инициализирует новый экземпляр класса[`ShaderMaterial`](../shadermaterial). |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques) { get; } | Получает все доступные техники, определенные в этом материале. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Получает перечислитель для перечисления внутренних слотов текстуры. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство, идентифицированное по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Устанавливает текстуру в указанный слот |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Форматирует объект в строку |

### Смотрите также

* class [Material](../material)
* пространство имен [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
