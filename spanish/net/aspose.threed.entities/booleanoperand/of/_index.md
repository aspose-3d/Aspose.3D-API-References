---
title: "BooleanOperand.Of"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BooleanOperand. Construye una instancia de BooleanOperand a partir de un nodo; se requiere una entidad válida que implemente IMeshConvertible"
type: docs
weight: 10
url: /es/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Construye una instancia de [`BooleanOperand`](../) a partir de un nodo; se requiere una entidad válida que implemente [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | Node | Una instancia de [`Node`](../../../aspose.threed/node/) con una entidad válida que implemente [`IMeshConvertible`](../../imeshconvertible/) |

### Valor de retorno

Una instancia de [`BooleanOperand`](../)

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *node* es nulo. |
| InvalidOperationException | Se lanza cuando no se encuentra ninguna entidad que implemente [`IMeshConvertible`](../../imeshconvertible/) bajo este nodo |

### Ver también

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Construye una instancia de [`BooleanOperand`](../) a partir de una instancia desnuda de [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | Entity | La malla utilizada como operando de la operación Booleana, puede ser una instancia de [`IMeshConvertible`](../../imeshconvertible/) o [`HalfSpace`](../../halfspace/). |

### Valor de retorno

Una instancia de [`BooleanOperand`](../)

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *mesh* es nulo. |

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


