---
title: "Matrix4.Scale"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4 Methode. Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert"
type: docs
weight: 50
url: /de/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | Vector3 | Skalierungsfaktoren gelten für die x-Achse, die y-Achse und die z-Achse |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Skalierungsoperation erstellt.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert.

```csharp
public static Matrix4 Scale(double s)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | Double | Skalierungsfaktoren gelten für alle Achsen |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Skalierungsoperation erstellt.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | Double | Skalierungsfaktoren gelten für die x-Achse |
| sy | Double | Skalierungsfaktoren gelten für die y-Achse |
| sz | Double | Skalierungsfaktoren gelten für die z-Achse |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Skalierungsoperation erstellt.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


