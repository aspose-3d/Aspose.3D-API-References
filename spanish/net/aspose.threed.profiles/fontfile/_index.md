---
title: "Clase FontFile"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.FontFile. El archivo de fuentes contiene definiciones de glifos y se usa para crear un perfil de texto"
type: docs
weight: 1720
url: /es/net/aspose.threed.profiles/fontfile/
---
## FontFile class

El archivo de fuente contiene definiciones de glifos, y se usa para crear un perfil de texto.

```csharp
public abstract class FontFile : A3DObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Cargar FontFile desde el nombre de archivo |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Analizar FontFile a partir de bytes |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


