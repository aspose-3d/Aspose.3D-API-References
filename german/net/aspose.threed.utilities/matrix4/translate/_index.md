---
title: "Matrix4.Translate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4 Methode. Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt"
type: docs
weight: 60
url: /de/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt

```csharp
public static Matrix4 Translate(Vector3 t)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| t | Vector3 | Übersetzungsversatz |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Übersetzungsoperation erstellt.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tx | Double | X-Koordinaten-Versatz |
| ty | Double | Y-Koordinaten-Versatz |
| tz | Double | Z-Koordinaten-Versatz |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Übersetzungsoperation erstellt.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


