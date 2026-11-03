---
title: "PolygonModifier.MergeMesh"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PolygonModifier. Convertir une scène entière en un seul maillage transformé. Les éléments de sommet comme les normales/coordonnées de texture ne sont pas encore pris en charge."
type: docs
weight: 50
url: /fr/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

Convertir une scène complète en un seul maillage transformé. Les éléments de sommet comme les normales/coordonnées de texture ne sont pas encore pris en charge.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scène | Scène | La scène à fusionner |

### Valeur de retour

Le maillage fusionné

## Exemples

Le code suivant montre comment fusionner tous les objets d'une scène en un seul maillage.

```csharp
//Le fichier d’entrée peut contenir plusieurs objets
var scene = Scene.FromFile("input.fbx");
//Maintenant, fusionnez-les en un seul maillage
Mesh merged = PolygonModifier.MergeMesh(scene);
//Ensuite, nous l'enregistrons dans un fichier avec un seul maillage
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Voir aussi

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### Voir aussi

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet comme les normales/coordonnées de texture ne sont pas encore pris en charge.

```csharp
public static Mesh MergeMesh(Node node)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Nœud | Le nœud à fusionner |

### Valeur de retour

Maillage fusionné

## Exemples

Le code suivant montre comment fusionner tous les objets des nœuds en un seul maillage.

```csharp
//Le fichier d’entrée peut contenir plusieurs objets
var scene = Scene.FromFile("input.fbx");
//Maintenant, fusionnez-les en un seul maillage
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//Ensuite, nous l'enregistrons dans un fichier avec un seul maillage
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Voir aussi

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


