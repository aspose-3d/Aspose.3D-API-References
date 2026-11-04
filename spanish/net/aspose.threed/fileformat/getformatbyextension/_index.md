---
title: "FileFormat.GetFormatByExtension"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método FileFormat. Obtiene el formato de archivo preferido a partir del nombre de la extensión de archivo. El nombre de la extensión debe comenzar con un punto."
type: docs
weight: 470
url: /es/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

Obtiene el formato de archivo preferido a partir del nombre de la extensión del archivo. El nombre de la extensión debe comenzar con un punto ('.').

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensionName | String | El nombre de la extensión comenzó con '.' para consultar. |

### Valor de retorno

Instancia de [`FileFormat`](../), de lo contrario se devuelve null.

## Ejemplos

El siguiente código muestra cómo guardar la escena en memoria usando el formato especificado

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### Ver también

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


