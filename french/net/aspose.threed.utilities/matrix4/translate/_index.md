---
title: "Matrix4.Translate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Matrix4. Crée une matrice qui translate le long de l'axe x, l'axe y et l'axe z"
type: docs
weight: 60
url: /fr/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

Crée une matrice qui traduit le long des axes x, y et z

```csharp
public static Matrix4 Translate(Vector3 t)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| t | Vector3 | Décalage de translation |

## Exemples

Le code suivant montre comment créer une matrice pour une opération de translation.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

Crée une matrice qui traduit le long des axes x, y et z

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tx | Double | Décalage de la coordonnée X |
| ty | Double | Décalage de la coordonnée Y |
| tz | Double | Décalage de la coordonnée Z |

## Exemples

Le code suivant montre comment créer une matrice pour une opération de translation.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


