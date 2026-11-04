---
title: "PlyFormat.Encode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PlyFormat. Codifica la entidad y guarda el resultado en el flujo"
type: docs
weight: 20
url: /es/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

Codifica la entidad y guarda el resultado en el flujo.

```csharp
public void Encode(Entity entity, Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| stream | Stream | El flujo al que escribir, este método no cerrará este flujo |

## Ejemplos

El siguiente código muestra cómo codificar una malla en un archivo PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

Codifica la entidad y guarda el resultado en el flujo.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| stream | Stream | El flujo al que escribir, este método no cerrará este flujo |
| opt | PlySaveOptions | Opciones de guardado |

## Ejemplos

El siguiente código muestra cómo codificar una malla en un archivo PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

Codifica la entidad y guarda el resultado en un archivo externo.

```csharp
public void Encode(Entity entity, string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | String | El archivo al que escribir |

## Ejemplos

El siguiente código muestra cómo codificar una malla en un archivo PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

Codifica la entidad y guarda el resultado en un archivo externo.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | String | El archivo al que escribir |
| opt | PlySaveOptions | Opciones de guardado |

## Ejemplos

El siguiente código muestra cómo codificar una malla en un archivo PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Ver también

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


