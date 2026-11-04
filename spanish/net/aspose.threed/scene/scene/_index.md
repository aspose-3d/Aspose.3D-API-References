---
title: "Scene.Scene"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Constructor de Scene. Inicializa una nueva instancia de la clase Scene"
type: docs
weight: 10
url: /es/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

Inicializa una nueva instancia de la clase [`Scene`](../).

```csharp
public Scene()
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

Inicializa una nueva instancia de la clase [`Scene`](../) con una entidad adjunta a un nuevo nodo.

```csharp
public Scene(Entity entity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad inicial que se adjunta a la escena |

## Ejemplos

El siguiente código muestra cómo crear un [`Scene`](../) directamente a partir de un [`Entity`](../../entity/):

```csharp
var scene = new Scene(new Box());
```

### Ver también

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

Inicializa una nueva instancia de la clase [`Scene`](../) como una subescena.

```csharp
public Scene(Scene parentScene, string name)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parentScene | Escena | La escena padre. |
| nombre | String | Nombre de la escena. |

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


