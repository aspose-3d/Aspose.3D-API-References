---
title: "Scene.AssetInfo"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Eigenschaft. Ruft die übergeordnete Asset-Information ab oder legt sie fest"
type: docs
weight: 50
url: /de/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

Liest oder setzt die Top‑Level‑Asset-Informationen.

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

Die Dokumentinformationen.

## Beispiele

Der folgende Code zeigt, wie man die Anwendungsinformationen aus einer FBX-Datei liest:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### Siehe auch

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


