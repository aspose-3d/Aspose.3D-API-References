---
title: "Enum StencilAction"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Render.StencilAction enum. Las acciones de prueba de stencil"
type: docs
weight: 2430
url: /es/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

Las acciones de la prueba de stencil

```csharp
public enum StencilAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Keep | `0` | Mantener el valor actual |
| Zero | `1` | Establece el valor del búfer de stencil a 0 |
| Replace | `2` | Establece el búfer de stencil a ref donde se define en [`StencilReference`](../renderstate/stencilreference/) |
| Increment | `3` | Incrementa el valor actual del búfer de stencil, lo limita al valor máximo. |
| IncrementWrap | `4` | Incrementa el valor actual del búfer de stencil y lo envuelve a cero cuando alcanza el valor máximo. |
| Decrement | `5` | Incrementa el valor actual del búfer de stencil, lo limita a 0. |
| DecrementWrap | `6` | Decrementa el valor actual del búfer de stencil y lo envuelve al valor máximo cuando llega a cero. |
| Invert | `7` | Invierte bit a bit el valor actual del búfer de stencil. |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


