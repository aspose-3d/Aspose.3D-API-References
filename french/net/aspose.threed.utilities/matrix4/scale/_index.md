---
title: "Matrix4.Scale"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Matrix4. Crée une matrice qui met à l'échelle le long de l'axe x, l'axe y et l'axe z"
type: docs
weight: 50
url: /fr/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

Crée une matrice qui met à l'échelle le long des axes x, y et z.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | Vector3 | Les usines de mise à l'échelle s'appliquent à l'axe x, l'axe y et l'axe z |

## Exemples

Le code suivant montre comment créer une matrice pour une opération d'échelle.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

Crée une matrice qui met à l'échelle le long des axes x, y et z.

```csharp
public static Matrix4 Scale(double s)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | Double | Les usines de mise à l'échelle s'appliquent à tous les axes |

## Exemples

Le code suivant montre comment créer une matrice pour une opération d'échelle.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Crée une matrice qui met à l'échelle le long des axes x, y et z.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sx | Double | Le redimensionnement des usines s'applique à l'axe x |
| sy | Double | Le redimensionnement des usines s'applique à l'axe y |
| sz | Double | Le redimensionnement des usines s'applique à l'axe z |

## Exemples

Le code suivant montre comment créer une matrice pour une opération d'échelle.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


