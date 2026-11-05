---
title: "BooleanOperand.Of"
second_title: "Aspose.3D for .NET API Referansı"
description: "BooleanOperand yöntemi. Bir düğümden BooleanOperand örneği oluşturur, geçerli bir IMeshConvertible uygulayan varlık gereklidir"
type: docs
weight: 10
url: /tr/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Bir düğümden [`BooleanOperand`](../) örneği oluşturun, geçerli bir varlık [`IMeshConvertible`](../../imeshconvertible/) uygulamalıdır

```csharp
public static BooleanOperand Of(Node node)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | Node | Geçerli bir varlık [`IMeshConvertible`](../../imeshconvertible/) uygulayan bir [`Node`](../../../aspose.threed/node/) örneği |

### Dönüş Değeri

[`BooleanOperand`](../) örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *node* null olduğunda ortaya çıkar. |
| InvalidOperationException | Bu düğüm altında [`IMeshConvertible`](../../imeshconvertible/) uygulayan hiçbir varlık bulunmadığında ortaya çıkar |

### Ayrıca Bakınız

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Boş bir [`IMeshConvertible`](../../imeshconvertible/) örneğinden bir [`BooleanOperand`](../) örneği oluşturun.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | Entity | Boolean işleminin operandı olarak kullanılan ağ, bir [`IMeshConvertible`](../../imeshconvertible/) veya [`HalfSpace`](../../halfspace/) örneği olabilir |

### Dönüş Değeri

[`BooleanOperand`](../) örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *mesh* null olduğunda ortaya çıkar. |

### Ayrıca Bakınız

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Ayrıca Bakınız

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


