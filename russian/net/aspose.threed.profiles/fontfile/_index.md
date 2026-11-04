---
title: "Класс FontFile"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.FontFile. Файл шрифта содержит определения глифов, используемых для создания текстового профиля."
type: docs
weight: 1720
url: /ru/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Файл шрифта содержит определения глифов, он используется для создания текстового профиля.

```csharp
public abstract class FontFile : A3DObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Загрузить FontFile из имени файла |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Разобрать FontFile из байтов |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

## Примеры

Следующий код показывает, как создать 3D‑сетку из текста, используя указанный файл шрифта.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


