---
title: "Clase AssetInfo"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.AssetInfo. Información del activo. La información del activo puede adjuntarse a una Scene. La Scene hija puede tener su propio AssetInfo para sobrescribir la definición del padre"
type: docs
weight: 130
url: /es/net/aspose.threed/assetinfo/
---
## AssetInfo class

Información del activo. La información del activo puede adjuntarse a un [`Scene`](../scene/). La [`Scene`](../scene/) hija puede tener su propio `AssetInfo` para sobrescribir la definición del padre.

```csharp
public class AssetInfo : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | Inicializa una nueva instancia de la clase `AssetInfo`. |
| [AssetInfo](assetinfo/#constructor_1)(string) | Inicializa una nueva instancia de la clase `AssetInfo`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | Obtiene o establece el color ambiental predeterminado de este activo |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | Obtiene o establece la aplicación que creó este activo |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | Obtiene o establece el nombre del proveedor de la aplicación |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | Obtiene o establece la versión de la aplicación que creó este activo. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | Obtiene o establece el autor de este activo |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | Obtiene o establece el sistema de coordenadas/vector ascendente/vector frontal de la información del activo. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | Obtiene o establece el comentario de este activo. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | Obtiene o establece el sistema de coordenadas utilizado en este activo. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | Obtiene o establece el copyright del documento |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | Obtiene o establece la hora de creación de este activo |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | Obtiene o establece el vector frontal utilizado en este activo. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | Obtiene o establece las palabras clave de este activo |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | Obtiene o establece la hora de modificación de este activo |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | Obtiene o establece el número de revisión de este activo, usualmente usado en sistemas de control de versiones. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | Obtiene o establece el asunto de este activo |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | Obtiene o establece el título de este activo |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | Obtiene o establece la unidad de longitud utilizada en este activo. p. ej., cm/m/km/pulgada/pies |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | Obtiene o establece el factor de escala a metros del mundo real. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | Obtiene o establece el vector ascendente utilizado en este activo. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | Obtiene o establece la URL de este activo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

## Ejemplos

El siguiente código muestra cómo leer la información del activo desde un archivo fbx:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### Ver también

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


