---
title: "Clase AxisSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.AxisSystem. El sistema de ejes es una combinación del vector ascendente del sistema de coordenadas y el vector frontal"
type: docs
weight: 150
url: /es/net/aspose.threed/axissystem/
---
## AxisSystem class

El sistema de ejes es una combinación de sistema de coordenadas, vector ascendente y vector frontal.

```csharp
public class AxisSystem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | Construye un nuevo sistema de ejes |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | Construye un nuevo sistema de ejes |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | Obtiene el sistema de coordenadas de este sistema de ejes. |
| [Front](../../aspose.threed/axissystem/front/) { get; } | Obtiene el vector frontal de este sistema de ejes |
| [Up](../../aspose.threed/axissystem/up/) { get; } | Obtiene el vector ascendente de este sistema de ejes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | Crear `AxisSystem` a partir de [`AssetInfo`](../assetinfo/) |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | Crear una matriz utilizada para convertir del sistema de ejes actual al sistema de ejes objetivo. |

### Ver también

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


