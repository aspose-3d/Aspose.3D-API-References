---
title: "Структура EndPoint"
second_title: "Справочник API Aspose.3D для .NET"
description: "Структура Aspose.ThreeD.Entities.EndPoint. Конечная точка для обрезки кривой может быть параметром или декартовой точкой"
type: docs
weight: 390
url: /ru/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

Конечная точка для обрезки кривой может быть значением параметра или декартовой точкой.

```csharp
public struct EndPoint
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EndPoint](endpoint/#constructor_1)(double) | Создать `EndPoint` из реального параметра. |
| [EndPoint](endpoint/#constructor)(Vector3) | Создать `EndPoint` из декартовой точки. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint/) { get; } | Получает конечную точку как декартовую точку или бросает исключение. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue/) { get; } | Получает конечную точку как реальный параметр или бросает исключение. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint/) { get; } | Является ли конечная точка декартовой точкой? |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree/)(double) | Создать конечную точку, измеряемую в градусах. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian/)(double) | Создайте конечную точку, измеряемую в радианах. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring/)() | Возвращает строковое представление текущей конечной точки. |

### См. также

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


