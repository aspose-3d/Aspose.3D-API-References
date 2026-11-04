---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método FileSystem. Inicializa un nuevo FileSystem que solo accede al directorio local. Todas las lecturas/escrituras de archivos en esta instancia de FileSystem se mapearán al directorio especificado"
type: docs
weight: 20
url: /es/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Inicializa un nuevo [`FileSystem`](../) que solo accede al directorio local. Todas las lecturas/escrituras de archivos en esta instancia de FileSystem se mapearán al directorio especificado.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| directorio | String | El directorio en tu sistema de archivos físico como el directorio raíz virtual. |

### Valor de retorno

Una nueva instancia del sistema de archivos para proporcionar acceso local a archivos

### Excepciones

| excepción | condición |
| --- | --- |
| FileNotFoundException | Lanzado cuando no se puede encontrar el directorio. |

## Ejemplos

El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un directorio dado

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crea una instancia de opciones de carga y especifica un sistema de archivos local
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//cargar el archivo
var scene = Scene.FromFile(inputFile, opt);
```

### Ver también

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


