---
title: "Clase Watermark"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Utilities.Watermark class. Utilidad para codificar/decodificar marca de agua ciega hacia/desde una malla"
type: docs
weight: 2950
url: /es/net/aspose.threed.utilities/watermark/
---
## Watermark class

Utilidad para codificar/decodificar marca de agua ciega hacia/desde una malla.

```csharp
public class Watermark
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | Decodificar la marca de agua de una malla |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | Decodificar la marca de agua de una malla |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | Codificar un texto en la marca de agua ciega de la malla. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | Codificar un texto en la marca de agua ciega de la malla. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | Codificar un texto en la marca de agua ciega de la malla. |

## Observaciones

Ambos [`EncodeWatermark`](./encodewatermark/) y [`DecodeWatermark`](./decodewatermark/) realizarán la verificación de licencia. El uso en modo de prueba lanzará una excepción; puedes usar [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones.

## Ejemplos

El siguiente código muestra cómo codificar una marca de agua ciega en una malla y decodificarla.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


