---
title: "BooleanOperand.Of"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode BooleanOperand. Membuat instance BooleanOperand dari sebuah node, diperlukan entitas yang valid yang mengimplementasikan IMeshConvertible"
type: docs
weight: 10
url: /id/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Buat sebuah instance [`BooleanOperand`](../) dari sebuah node, diperlukan entitas yang valid yang mengimplementasikan [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Node node)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Sebuah instance [`Node`](../../../aspose.threed/node/) dengan entitas yang valid yang mengimplementasikan [`IMeshConvertible`](../../imeshconvertible/). |

### Nilai Kembalian

Sebuah instance dari [`BooleanOperand`](../).

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *node* bernilai null. |
| InvalidOperationException | Dilempar ketika tidak ada entitas yang mengimplementasikan [`IMeshConvertible`](../../imeshconvertible/) ditemukan di bawah node ini. |

### Lihat Juga

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Buat sebuah instance [`BooleanOperand`](../) dari sebuah instance [`IMeshConvertible`](../../imeshconvertible/) yang mentah.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | Entity | Mesh yang digunakan sebagai operand operasi Boolean, dapat berupa instance dari [`IMeshConvertible`](../../imeshconvertible/) atau [`HalfSpace`](../../halfspace/). |

### Nilai Kembalian

Sebuah instance dari [`BooleanOperand`](../).

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *mesh* bernilai null. |

### Lihat Juga

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Lihat Juga

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


