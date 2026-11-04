---
title: "Clase FileFormat"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.FileFormat. Definición del formato de archivo"
type: docs
weight: 1060
url: /es/net/aspose.threed/fileformat/
---
## FileFormat class

Definición del formato de archivo

```csharp
public class FileFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtiene el tipo de contenido del formato de archivo |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtiene el nombre de la extensión de este tipo. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtiene los nombres de las extensiones de este tipo. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtiene el tipo de formato de archivo |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtiene la versión del formato de archivo |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | Acceso a todos los formatos compatibles |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | Detecte el formato de archivo a partir del nombre del archivo, el archivo debe ser legible para que Aspose.3D pueda detectar el formato mediante el encabezado del archivo. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | Detecte el formato de archivo a partir del flujo de datos, el nombre del archivo es opcional para adivinar tipos que no tienen encabezado mágico. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | Obtiene el formato de archivo preferido a partir del nombre de la extensión del archivo. El nombre de la extensión debe comenzar con un punto ('.'). |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crea opciones de carga predeterminadas para este formato de archivo |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crea opciones de guardado predeterminadas para este formato de archivo |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatea a cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | Formato de archivo de fabricación aditiva |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | Formato de exportador de escena ASCII de 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Formato web de Aspose.3D. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | Formato de archivo 3D de Blender |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Formato de archivo Collada |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | Formato de archivo de 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | Formato de archivo FBX ASCII, con versión 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Formato de archivo FBX binario, con versión 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | Formato de archivo FBX ASCII, con versión 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Formato de archivo FBX binario, con versión 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | Formato de archivo FBX ASCII, con versión 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Formato de archivo FBX binario, con versión 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | Formato de archivo FBX ASCII, con versión 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Formato de archivo FBX binario, con versión 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | Formato de archivo FBX ASCII, con versión 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Formato de archivo FBX binario, con versión 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | Formato de archivo FBX ASCII, con versión 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Formato de archivo FBX binario, con versión 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | Formato de archivo FBX ASCII, con versión 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Formato de archivo FBX binario, con versión 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF del Grupo Khronos |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF versión 2.0 del Grupo Khronos |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF versión 2.0 del Grupo Khronos |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF en formato binario del Grupo Khronos |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | Archivo HTML5 |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | Modelo de datos de Industry Foundation Classes ISO 16739-1. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya en formato ASCII |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya en formato binario |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | Archivo PCL Point Cloud Data en modo ASCII |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | Archivo PCL Point Cloud Data en modo binario |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Archivo Siemens JT Versión 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Archivo Siemens JT Versión 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | Formato de archivo STL ASCII |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | Formato de archivo STL binario |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Formato de archivo Universal3D |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | Descripción Universal de Escena |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | Descripción Universal de Escena en formato ASCII. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | Descripción Universal de Escena comprimida |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | El Lenguaje de Modelado de Realidad Virtual |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Formato de archivo Obj de Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | Archivo X de DirectX en formato binario |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | Archivo X de DirectX en formato binario |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Archivo de nube de puntos Xyz |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | Archivo Zip que contiene otros formatos de archivo 3D. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Malla Google Draco |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Formato de Fabricación 3D de Microsoft |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Formato de Documento Portátil de Adobe |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | Formato de Archivo Polygon o Formato de Triángulo Stanford |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato binario |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato de texto |

### Ver también

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


