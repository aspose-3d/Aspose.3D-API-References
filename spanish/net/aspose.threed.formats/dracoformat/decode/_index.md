---
title: "DracoFormat.Decode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método DracoFormat. Decodifica la nube de puntos o malla del nombre de archivo especificado"
type: docs
weight: 10
url: /es/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

Decodifica la nube de puntos o malla desde el nombre de archivo especificado

```csharp
public Geometry Decode(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El nombre de archivo contiene el archivo drc |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/) depende del contenido del archivo

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Se lanza cuando no se pudo leer el archivo |

## Ejemplos

El siguiente código muestra cómo codificar y decodificar una Mesh a/de una matriz de bytes:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//decodificar malla del formato Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

Decodifica la nube de puntos o malla desde datos en memoria

```csharp
public Geometry Decode(byte[] data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | Byte[] | Los bytes crudos de drc |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/) depende del contenido

### Excepciones

| excepción | condición |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | Se lanza cuando los datos están malformados. |

## Ejemplos

El siguiente código muestra cómo codificar y decodificar una Mesh a/de una matriz de bytes:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//decodificar malla del formato Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


