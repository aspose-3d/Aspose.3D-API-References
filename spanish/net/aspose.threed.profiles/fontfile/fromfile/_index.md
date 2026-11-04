---
title: "FontFile.FromFile"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método FontFile. Cargar FontFile desde el nombre de archivo"
type: docs
weight: 10
url: /es/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Cargar FontFile desde el nombre de archivo

```csharp
public static FontFile FromFile(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Ruta al archivo de fuente |

### Valor de retorno

Instancia FontFile

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Se lanza cuando falla la lectura del archivo. |

## Ejemplos

El siguiente código muestra cómo crear una malla 3D a partir del texto usando el archivo de fuente especificado.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Ver también

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


