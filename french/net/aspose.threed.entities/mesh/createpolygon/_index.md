---
title: "Mesh.CreatePolygon"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Mesh. Crée un nouveau polygone avec tous les sommets définis dans les indices. Pour créer le polygone sommet par sommet, veuillez utiliser PolygonBuilder."
type: docs
weight: 60
url: /fr/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Crée un nouveau polygone avec tous les sommets définis dans *indices*. Pour créer le polygone sommet par sommet, veuillez utiliser [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| indices | Int32[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |
| offset | Int32 | Le décalage du premier indice du polygone |
| length | Int32 | La longueur des indices |

## Exemples

Le code suivant montre comment créer un nouveau polygone avec les indices des points de contrôle.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Crée un nouveau polygone avec tous les sommets définis dans *indices*. Pour créer le polygone sommet par sommet, veuillez utiliser [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| indices | Int32[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |

## Exemples

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Crée un polygone avec 4 sommets (quad)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| v1 | Int32 | Indice du premier sommet |
| v2 | Int32 | Indice du deuxième sommet |
| v3 | Int32 | Indice du troisième sommet |
| v4 | Int32 | Indice du quatrième sommet |

## Exemples

Le code suivant montre comment créer un nouveau polygone avec les indices des points de contrôle.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Crée un polygone avec 3 sommets (triangle)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| v1 | Int32 | Indice du premier sommet |
| v2 | Int32 | Indice du deuxième sommet |
| v3 | Int32 | Indice du troisième sommet |

## Exemples

Le code suivant montre comment créer un nouveau polygone avec les indices des points de contrôle.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


