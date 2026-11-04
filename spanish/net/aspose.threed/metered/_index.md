---
title: "Clase Metered"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Metered clase. Proporciona métodos para establecer la clave medida"
type: docs
weight: 1620
url: /es/net/aspose.threed/metered/
---
## Metered class

Proporciona métodos para establecer la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada medida. Si compra una licencia medida, al iniciar la aplicación, se debe llamar a esta API; normalmente, esto es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar tal caso, debe comprobar regularmente el estado de la licencia, y si está en estado de evaluación, llamar a esta API nuevamente. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | Obtiene crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada medida

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

el archivo jar del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ver también

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


