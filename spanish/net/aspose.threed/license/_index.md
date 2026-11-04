---
title: "Clase License"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.License. Proporciona métodos para licenciar el componente"
type: docs
weight: 1610
url: /es/net/aspose.threed/license/
---
## License class

Proporciona métodos para licenciar el componente.

```csharp
public class License
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | Licencia el componente. |

## Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado llamador, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado llamador.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

el archivo jar del componente:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ver también

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


