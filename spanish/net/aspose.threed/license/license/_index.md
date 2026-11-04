---
title: "License.License"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Constructor License. Inicializa una nueva instancia de esta clase."
type: docs
weight: 10
url: /es/net/aspose.threed/license/license/
---
## License constructor

Inicializa una nueva instancia de esta clase.

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


