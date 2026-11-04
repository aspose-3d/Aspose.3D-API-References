---
title: "BooleanOperand.Of"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BooleanOperand. Создаёт экземпляр BooleanOperand из узла, требуется корректный объект, реализующий IMeshConvertible"
type: docs
weight: 10
url: /ru/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Создайте экземпляр [`BooleanOperand`](../) из узла, требуется корректный объект, реализующий [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | Node | Экземпляр [`Node`](../../../aspose.threed/node/) с корректным объектом, реализующим [`IMeshConvertible`](../../imeshconvertible/) |

### Возвращаемое значение

Экземпляр [`BooleanOperand`](../)

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *node* равно null. |
| InvalidOperationException | Выбрасывается, когда под этим узлом не найден объект, реализующий [`IMeshConvertible`](../../imeshconvertible/) |

### См. также

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Создайте экземпляр [`BooleanOperand`](../) из отдельного экземпляра [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | Entity | Сетка, используемая в качестве операнда булевой операции; может быть экземпляром [`IMeshConvertible`](../../imeshconvertible/) или [`HalfSpace`](../../halfspace/). |

### Возвращаемое значение

Экземпляр [`BooleanOperand`](../)

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *mesh* равно null. |

### См. также

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### См. также

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


