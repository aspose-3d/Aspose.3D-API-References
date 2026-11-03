---
title: "Scene.AssetInfo"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Scene. Λαμβάνει ή ορίζει τις πληροφορίες του ανώτερου επιπέδου περιουσιακού στοιχείου"
type: docs
weight: 50
url: /el/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

Λαμβάνει ή ορίζει τις πληροφορίες του κορυφαίου στοιχείου

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

Οι πληροφορίες του εγγράφου.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τις πληροφορίες της εφαρμογής από ένα αρχείο FBX:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### Δείτε επίσης

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


