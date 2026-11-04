---
title: "IOConfig.LookupPaths"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad IOConfig. Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permiten a Aspose.3D buscar archivos externos para cargar"
type: docs
weight: 50
url: /es/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo.

```csharp
public List<string> LookupPaths { get; set; }
```

## Ejemplos

El siguiente código muestra cómo especificar manualmente las texturas de búsqueda, para que el importador pueda encontrarlas

```csharp
var opt = new ObjLoadOptions();
//Especifique las rutas de búsqueda, para que las texturas puedan localizarse.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### Ver también

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


