---
title: "PolygonModifier.BuildTangentBinormal"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PolygonModifier. Cela créera les tangentes et binormales sur tous les maillages de la scène. La normale est requise si aucune normale n'existe sur le maillage ; elle créera également les données de normales à partir de la position. L'UV est également requis ; le maillage sera ignoré s'il n'y a pas d'UV défini."
type: docs
weight: 20
url: /fr/net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## BuildTangentBinormal(Scene) {#buildtangentbinormal_1}

Cela créera les tangentes et les binormales sur tous les maillages de la scène. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, le maillage sera ignoré s'il n'y a pas d'UV défini.

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## BuildTangentBinormal(Mesh) {#buildtangentbinormal}

Cela créera les tangentes et les binormales sur le maillage. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, une exception sera levée si aucun UV n'est trouvé.

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### Voir aussi

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


