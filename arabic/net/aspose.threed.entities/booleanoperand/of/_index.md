---
title: "BooleanOperand.Of"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة BooleanOperand. أنشئ مثيلاً من BooleanOperand من عقدة؛ يتطلب كيانًا صالحًا ينفذ IMeshConvertible"
type: docs
weight: 10
url: /ar/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

أنشئ مثيلاً من [`BooleanOperand`](../) من عقدة، يتطلب كيانًا صالحًا ينفذ [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| node | Node | كائن [`Node`](../../../aspose.threed/node/) مع كيان صالح يطبق [`IMeshConvertible`](../../imeshconvertible/) |

### قيمة الإرجاع

مثال لـ [`BooleanOperand`](../)

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رفع الاستثناء عندما تكون *node* null. |
| InvalidOperationException | يتم رفع الاستثناء عندما لا يتم العثور على أي كيان يطبق [`IMeshConvertible`](../../imeshconvertible/) تحت هذه العقدة. |

### انظر أيضًا

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

إنشاء مثال [`BooleanOperand`](../) من مثال [`IMeshConvertible`](../../imeshconvertible/) فارغ.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| mesh | Entity | المجسم المستخدم كمعامل عملية Boolean، يمكن أن يكون مثالًا لـ [`IMeshConvertible`](../../imeshconvertible/) أو [`HalfSpace`](../../halfspace/). |

### قيمة الإرجاع

مثال لـ [`BooleanOperand`](../)

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رفع الاستثناء عندما تكون *mesh* null. |

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


