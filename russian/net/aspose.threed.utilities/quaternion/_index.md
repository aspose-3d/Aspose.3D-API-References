---
title: "Структура Quaternion"
second_title: "Справочник API Aspose.3D для .NET"
description: "Структура Aspose.ThreeD.Utilities.Quaternion. Кватернион обычно используется для выполнения вращения в компьютерной графике"
type: docs
weight: 2810
url: /ru/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Кватернион обычно используется для выполнения вращения в компьютерной графике.

```csharp
public struct Quaternion
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | Инициализирует новый экземпляр класса `Quaternion`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | Получает длину кватерниона |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | Создаёт кватернион вокруг заданной оси и вращает по часовой стрелке |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | Создаёт кватернион из заданного угла Эйлера |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | Создаёт кватернион из заданного угла Эйлера |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | Создаёт кватернион, вращающийся от исходного направления к целевому |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | Заполняет этот кватернион интерполированным значением между заданными аргументами кватернионов для t в диапазоне от начального до конечного. |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | Выполняет сферическую линейную интерполяцию между двумя значениями |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | Конкатенирует два кватерниона |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | Возвращает сопряжённый кватернион текущего кватерниона |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | Скалярное произведение |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | Проверяет, равны ли два кватерниона |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | Преобразует кватернион в вращение, представленное углами Эйлера. Все компоненты указаны в радианах |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | Получает хеш‑код кватерниона |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | Возвращает обратный кватернион текущего кватерниона |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | Нормализует кватернион |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | Преобразует вращение, представленное кватернионом, в матрицу преобразования. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | Преобразует вращение, представленное кватернионом, в матрицу преобразования. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | Получает строковое представление кватерниона |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | Перегрузка оператора + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | Перегрузка оператора `/` |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | Оператор равенства для кватерниона |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | Оператор неравенства для кватерниона |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | Перегрузка оператора `*` (5 операторов) |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | Единичный кватернион. |
| [W](../../aspose.threed.utilities/quaternion/w/) | Компонент w. |
| [X](../../aspose.threed.utilities/quaternion/x/) | Компонента x. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | Компонента y. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | Компонента z. |

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


