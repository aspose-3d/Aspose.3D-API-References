---
title: "BooleanOperand.Of"
second_title: "Aspose.3D for .NET API 참조"
description: "BooleanOperand 메서드. 노드에서 BooleanOperand 인스턴스를 생성합니다. 유효한 엔터티가 IMeshConvertible을 구현해야 합니다"
type: docs
weight: 10
url: /ko/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

노드에서 [`BooleanOperand`](../) 인스턴스를 생성하려면, 구현된 유효한 엔터티 [`IMeshConvertible`](../../imeshconvertible/)가 필요합니다.

```csharp
public static BooleanOperand Of(Node node)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | Node | 유효한 엔터티를 구현한 [`Node`](../../../aspose.threed/node/) 인스턴스와 [`IMeshConvertible`](../../imeshconvertible/) |

### 반환 값

`[`BooleanOperand`](../) 인스턴스`

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *node*가 null인 경우 발생합니다. |
| InvalidOperationException | 이 노드 아래에서 [`IMeshConvertible`](../../imeshconvertible/)를 구현한 엔터티가 없을 때 발생합니다. |

### 또 보기

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

순수한 [`IMeshConvertible`](../../imeshconvertible/) 인스턴스로부터 [`BooleanOperand`](../) 인스턴스를 생성합니다.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | Entity | Boolean 연산의 피연산자로 사용되는 메시는 [`IMeshConvertible`](../../imeshconvertible/) 또는 [`HalfSpace`](../../halfspace/) 인스턴스가 될 수 있습니다. |

### 반환 값

`[`BooleanOperand`](../) 인스턴스`

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *mesh*가 null인 경우 발생합니다. |

### 또 보기

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### 또 보기

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


