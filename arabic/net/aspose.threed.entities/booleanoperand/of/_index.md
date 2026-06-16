---
title: "BooleanOperand.Of"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة BooleanOperand. أنشئ مثيلاً من BooleanOperand من عقدة، يلزم وجود كيان صالح يطبق IMeshConvertible"
type: docs
weight: 10
url: /ar/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

أنشئ مثيلاً من [`BooleanOperand`](../) من عقدة، يلزم وجود كيان صالح يطبق [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| node | Node | مثيل من [`Node`](../../../aspose.threed/node/) مع كيان صالح يطبق [`IMeshConvertible`](../../imeshconvertible/) |

### قيمة الإرجاع

مثيل من [`BooleanOperand`](../)

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرفع عندما تكون *node* فارغة. |
| InvalidOperationException | يُرفع عندما لا يُعثر على أي كيان يطبق [`IMeshConvertible`](../../imeshconvertible/) تحت هذه العقدة |

### انظر أيضًا

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

أنشئ مثيلاً من [`BooleanOperand`](../) من مثيل [`IMeshConvertible`](../../imeshconvertible/) مجرد.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| mesh | Entity | الشبكة المستخدمة كمعامل عملية Boolean، يمكن أن تكون مثيلاً من [`IMeshConvertible`](../../imeshconvertible/) أو [`HalfSpace`](../../halfspace/). |

### قيمة الإرجاع

مثيل من [`BooleanOperand`](../)

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرفع عندما تكون *mesh* فارغة. |

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### انظر أيضًا

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


