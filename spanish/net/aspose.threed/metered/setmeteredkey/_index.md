---
title: "Metered.SetMeteredKey"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Metered. Establece la clave pública y privada medida. Si compras una licencia medida al iniciar la aplicación, esta API debe llamarse normalmente; con eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar tal caso, deberías comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API de nuevo."
type: docs
weight: 20
url: /es/net/aspose.threed/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Establece la clave pública y privada medida. Si compra una licencia medida, al iniciar la aplicación, se debe llamar a esta API; normalmente, esto es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar tal caso, debe comprobar regularmente el estado de la licencia, y si está en estado de evaluación, llamar a esta API nuevamente.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | String | clave pública |
| privateKey | String | clave privada |

### Ver también

* class [Metered](../)
* namespace [Aspose.ThreeD](../../metered/)
* assembly [Aspose.3D](../../../)


