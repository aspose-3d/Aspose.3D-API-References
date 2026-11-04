---
title: "Структура Vector3"
second_title: "Справочник API Aspose.3D для .NET"
description: "Структура Aspose.ThreeD.Utilities.Vector3. Вектор с тремя компонентами"
type: docs
weight: 2880
url: /ru/net/aspose.threed.utilities/vector3/
---
## Vector3 structure

Вектор с тремя компонентами.

```csharp
public struct Vector3 : IComparable<Vector3>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Vector3](vector3/#constructor_2)(double) | Инициализирует новый экземпляр структуры `Vector3`. |
| [Vector3](vector3/#constructor)(FVector3) | Инициализирует новый экземпляр структуры `Vector3`. |
| [Vector3](vector3/#constructor_1)(Vector4) | Инициализирует новый экземпляр структуры `Vector3`. |
| [Vector3](vector3/#constructor_3)(double, double, double) | Инициализирует новый экземпляр структуры `Vector3`. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [One](../../aspose.threed.utilities/vector3/one/) { get; } | Получает единичный вектор (1, 1, 1) |
| static [UnitX](../../aspose.threed.utilities/vector3/unitx/) { get; } | Получает единичный вектор (1, 0, 0) |
| static [UnitY](../../aspose.threed.utilities/vector3/unity/) { get; } | Получает единичный вектор (0, 1, 0) |
| static [UnitZ](../../aspose.threed.utilities/vector3/unitz/) { get; } | Получает единичный вектор (0, 0, 1) |
| static [Zero](../../aspose.threed.utilities/vector3/zero/) { get; } | Получает единичный вектор (0, 0, 0) |
| [Item](../../aspose.threed.utilities/vector3/item/) { get; set; } |  |
| [Length](../../aspose.threed.utilities/vector3/length/) { get; } | Получает длину этого вектора. |
| [Length2](../../aspose.threed.utilities/vector3/length2/) { get; } | Получает квадрат длины. |

## Методы

| Имя | Описание |
| --- | --- |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween)(Vector3) | Вычисляет внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween_1)(Vector3, Vector3) | Вычисляет внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами |
| [CompareTo](../../aspose.threed.utilities/vector3/compareto/)(Vector3) | Сравнивает текущий вектор с другим экземпляром. |
| [Cos](../../aspose.threed.utilities/vector3/cos/)() | Вычисляет косинус для каждой компоненты |
| [Cross](../../aspose.threed.utilities/vector3/cross/)(Vector3) | Векторное произведение двух векторов |
| [Dot](../../aspose.threed.utilities/vector3/dot/)(Vector3) | Получает скалярное произведение двух векторов |
| override [Equals](../../aspose.threed.utilities/vector3/equals/)(object) | Проверяет, равны ли два Vector3 |
| override [GetHashCode](../../aspose.threed.utilities/vector3/gethashcode/)() | Получает хеш-код Vector3 |
| [Normalize](../../aspose.threed.utilities/vector3/normalize/)() | Нормализует этот экземпляр. |
| [Set](../../aspose.threed.utilities/vector3/set/)(double, double, double) | Устанавливает компоненты x/y/z за один вызов. |
| [Sin](../../aspose.threed.utilities/vector3/sin/)() | Вычисляет синус для каждой компоненты |
| override [ToString](../../aspose.threed.utilities/vector3/tostring/)() | Возвращает строку, представляющую текущий `Vector3`. |
| [operator +](../../aspose.threed.utilities/vector3/op_addition/) | Перегрузка оператора + |
| [operator /](../../aspose.threed.utilities/vector3/op_division/#op_division_1) | Перегрузка оператора / (2 оператора) |
| [operator ==](../../aspose.threed.utilities/vector3/op_equality/) | Оператор равенства для Vector3 |
| [explicit operator](../../aspose.threed.utilities/vector3/op_explicit/) |  |
| [operator !=](../../aspose.threed.utilities/vector3/op_inequality/) | Оператор неравенства для Vector3 |
| [operator *](../../aspose.threed.utilities/vector3/op_multiply/#op_multiply) | Перегрузка оператора * (3 оператора) |
| [operator -](../../aspose.threed.utilities/vector3/op_subtraction/) | Перегрузка оператора - (2 оператора) |

## Поля

| Имя | Описание |
| --- | --- |
| [X](../../aspose.threed.utilities/vector3/x/) | Компонента x. |
| [Y](../../aspose.threed.utilities/vector3/y/) | Компонента y. |
| [Z](../../aspose.threed.utilities/vector3/z/) | Компонента z. |

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


