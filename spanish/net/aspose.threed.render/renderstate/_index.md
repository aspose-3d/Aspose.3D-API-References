---
title: "Clase RenderState"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Render.RenderState. Estado de renderizado para construir la canalización. Los cambios realizados en el estado de renderizado no afectarán a las instancias de la canalización creadas"
type: docs
weight: 2330
url: /es/net/aspose.threed.render/renderstate/
---
## RenderState class

Estado de renderizado para construir el pipeline. Los cambios realizados en el estado de renderizado no afectarán a las instancias del pipeline creadas.

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RenderState](renderstate/)() | Constructor de `RenderState` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | Activar o desactivar la mezcla de fragmentos. |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | Obtiene o establece el color de mezcla donde se usa en ConstantColor |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | Activar o desactivar la eliminación de caras |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | Obtiene o establece qué cara será eliminada. |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | Obtiene o establece la función de comparación utilizada en la prueba de profundidad |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | Activar o desactivar la escritura de profundidad. |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | Activar o desactivar la prueba de profundidad. |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | Obtiene o establece cómo se mezcla el color. |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | Obtiene o establece cuál es el orden de la cara frontal. |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | Obtiene o establece el modo de renderizado del polígono. |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | Activar o desactivar la prueba de tijera |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | Obtiene o establece cómo se mezcla el color. |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | Obtiene el estado de stencil para la cara trasera. |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | Obtiene el estado de stencil para la cara frontal. |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | Obtiene o establece la máscara que se ANDea con la referencia y el valor de stencil almacenado cuando se realiza la prueba. |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | Obtiene o establece el valor de referencia para la prueba de stencil. |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | Activar o desactivar la prueba de stencil. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | Comparar el estado de renderizado con otra instancia |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | Elimine el `RenderState` y libere todos los recursos internos. |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | Devuelve el código hash de esta instancia. |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


