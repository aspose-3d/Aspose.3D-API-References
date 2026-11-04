---
title: "DracoFormat.Encode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método DracoFormat. Codifica la entidad al flujo especificado"
type: docs
weight: 20
url: /es/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

Codifica la entidad al flujo especificado

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| stream | Stream | El flujo al que se escribirán los datos codificados |
| opciones | DracoSaveOptions | Opciones adicionales para codificar la nube de puntos |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Se lanza cuando no se pudo leer del flujo |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

Codifica la entidad al archivo especificado

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| fileName | String | El nombre de archivo que se escribirá |
| opciones | DracoSaveOptions | Opciones adicionales para codificar la nube de puntos |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

Codifica la entidad a datos sin procesar Draco

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad a codificar |
| opciones | DracoSaveOptions | Opciones adicionales para codificar la nube de puntos |

### Valor de retorno

Los datos draco codificados representados en bytes

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


