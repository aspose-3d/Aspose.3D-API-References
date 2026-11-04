---
title: "Scene.AssetInfo"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Scene. Получает или задает информацию о верхнеуровневом ресурсе"
type: docs
weight: 50
url: /ru/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

Получает или задаёт информацию о верхнеуровневом ресурсе

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

Информация о документе.

## Примеры

Следующий код показывает, как прочитать информацию о приложении из файла FBX:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### См. также

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


