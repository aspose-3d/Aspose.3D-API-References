---
title: "Структура Matrix4"
second_title: "Справочник API Aspose.3D для .NET"
description: "Структура Aspose.ThreeD.Utilities.Matrix4. Реализация 4x4 матрицы"
type: docs
weight: 2790
url: /ru/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

Реализация матрицы 4x4.

```csharp
public struct Matrix4
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | Инициализирует новый экземпляр структуры `Matrix4`. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | Создайте `Matrix4` из экземпляра [`FMatrix4`](../fmatrix4/) |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Создаёт матрицу из 4 строк. |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Инициализирует новый экземпляр структуры `Matrix4`. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | Получает единичную матрицу. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | Получает определитель матрицы. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | Создайте матрицу вращения из кватерниона |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | Создайте матрицу вращения по углу вращения и оси |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | Создайте матрицу вращения из угла Эйлера |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | Создайте матрицу вращения из угла Эйлера |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | Создаёт матрицу, масштабирующую вдоль осей x, y и z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | Создаёт матрицу, масштабирующую вдоль осей x, y и z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | Создаёт матрицу, масштабирующую вдоль осей x, y и z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | Создаёт матрицу, перемещающую вдоль осей x, y и z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | Создаёт матрицу, перемещающую вдоль осей x, y и z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | Объединяет две матрицы |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | Инвертирует этот экземпляр. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | Нормализует этот экземпляр. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | Инициализирует матрицу с трансляцией/вращением/масштабом |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | Преобразует матрицу в массив. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | Возвращает строку, представляющую текущий `Matrix4`. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | Транспонирует этот экземпляр. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | Умножьте две матрицы (4 оператора) |

## Поля

| Имя | Описание |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | Элемент m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | Элемент m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | Элемент m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | Элемент m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | Элемент m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | Элемент m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | Элемент m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | Элемент m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | Элемент m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | Элемент m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | Элемент m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | Элемент m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | Элемент m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | Элемент m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | Элемент m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | Элемент m33. |

## Примеры

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


