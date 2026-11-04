---
title: "Estructura RelativeRectangle"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Utilities.RelativeRectangle struct. Rectángulo relativo La fórmula entre el componente relativo y el valor absoluto es Escala  Ancho de referencia  desplazamiento Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar"
type: docs
weight: 2830
url: /es/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Rectángulo relativo La fórmula entre el componente relativo y el valor absoluto es: Escala * (Ancho de referencia) + desplazamiento. Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar.

```csharp
public struct RelativeRectangle
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | Construir un `RelativeRectangle` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | Obtiene o establece el desplazamiento para la altura |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | Obtiene o establece el desplazamiento para el ancho |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | Obtiene o establece el desplazamiento para la coordenada X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | Obtiene o establece el desplazamiento para la coordenada Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | Altura relativa |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | Ancho relativo |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | Coordenada relativa X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | Coordenada relativa Y |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | Construir un `RelativeRectangle` con todos los campos de desplazamiento en cero y los campos de escala a partir de los parámetros dados. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | Convertir el rectángulo relativo a rectángulo absoluto |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | Convierte el valor de esta instancia a una cadena. |

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


