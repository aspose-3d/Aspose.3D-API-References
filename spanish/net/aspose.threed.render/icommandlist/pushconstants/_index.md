---
title: "ICommandList.PushConstants"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método ICommandList. Empuje la constante al pipeline"
type: docs
weight: 70
url: /es/net/aspose.threed.render/icommandlist/pushconstants/
---
## PushConstants(ShaderStage, byte[]) {#pushconstants}

Enviar la constante al pipeline

```csharp
public void PushConstants(ShaderStage stage, byte[] data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etapa | ShaderStage | ¿Qué etapa de shader consumirá los datos constantes? |
| datos | Byte[] | Los datos que se enviarán al shader |

### Ver también

* enum [ShaderStage](../../shaderstage/)
* interface [ICommandList](../)
* namespace [Aspose.ThreeD.Render](../../icommandlist/)
* assembly [Aspose.3D](../../../)

---

## PushConstants(ShaderStage, byte[], int) {#pushconstants_1}

Enviar la constante al pipeline

```csharp
public void PushConstants(ShaderStage stage, byte[] data, int size)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etapa | ShaderStage | ¿Qué etapa de shader consumirá los datos constantes? |
| datos | Byte[] | Los datos que se enviarán al shader |
| tamaño | Int32 | Bytes para escribir en el pipeline |

### Ver también

* enum [ShaderStage](../../shaderstage/)
* interface [ICommandList](../)
* namespace [Aspose.ThreeD.Render](../../icommandlist/)
* assembly [Aspose.3D](../../../)


