---
title: "Mesh.Optimize"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo Mesh. Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati"
type: docs
weight: 100
url: /it/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | Boolean | Ottimizza i dati degli elementi vertice duplicati |

### Valore di ritorno

Nuova istanza di mesh con uso compatto della memoria

## Esempi

Il codice seguente mostra come eliminare i punti di controllo duplicati da una mesh non ottimizzata:

```csharp
//Sphere.ToMesh genera 117 punti di controllo
var mesh = (new Sphere()).ToMesh();
//Dopo l'ottimizzazione, ci sono solo 86 punti di controllo, gli indici dei poligoni sono anche rimappati.
var optimized = mesh.Optimize(true);
```

### Vedi anche

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | Boolean | Ottimizza i dati degli elementi vertice duplicati |
| toleranceControlPoint | Single | La tolleranza per il punto di controllo, il valore predefinito è 1e-9 |
| toleranceNormal | Single | La tolleranza per normale/tangente/binormale, il valore predefinito è 1e-9 |
| toleranceUV | Single | La tolleranza per uv, il valore predefinito è 1e-9 |

### Valore di ritorno

Nuova istanza di mesh con uso compatto della memoria

### Vedi anche

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


