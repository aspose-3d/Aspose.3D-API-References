---
title: "Enum BoneLinkMode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Deformers.BoneLinkMode enum. Un modo de enlace de huesos se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica."
type: docs
weight: 200
url: /es/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica.

```csharp
public enum BoneLinkMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Normalize | `0` | En este modo, las transformaciones de los huesos hijos se normalizan con respecto a las transformaciones del hueso padre. |
| Additive | `1` | El modo aditivo calcula las transformaciones de los huesos hijos sumando sus propias transformaciones locales a las de sus huesos padres. |
| TotalOne | `2` | Total One asegura que las transformaciones combinadas del hueso padre y los huesos hijos resulten en una transformación combinada que se escale a una longitud total de una unidad. |

### Ver también

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


