---
title: "Mesh.Optimize"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Mesh. Βελτιστοποιεί τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου"
type: docs
weight: 100
url: /el/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Βελτιστοποιεί τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

```csharp
public Mesh Optimize(bool vertexElements)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | Boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |

### Τιμή επιστροφής

Νέα παρουσία πλέγματος με συμπαγή χρήση μνήμης

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αφαιρέσετε διπλότυπα σημεία ελέγχου από ένα μη βελτιστοποιημένο πλέγμα:

```csharp
//Το Sphere.ToMesh δημιουργεί 117 σημεία ελέγχου
var mesh = (new Sphere()).ToMesh();
//Μετά τη βελτιστοποίηση, υπάρχουν μόνο 86 σημεία ελέγχου, οι δείκτες των πολυγώνων επίσης επαναχρεωδούνται.
var optimized = mesh.Optimize(true);
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Βελτιστοποιεί τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | Boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |
| toleranceControlPoint | Single | Η ανοχή για το σημείο ελέγχου, η προεπιλεγμένη τιμή είναι 1e-9 |
| toleranceNormal | Single | Η ανοχή για normal/tangent/binormal, η προεπιλεγμένη τιμή είναι 1e-9 |
| toleranceUV | Single | Η ανοχή για uv, η προεπιλεγμένη τιμή είναι 1e-9 |

### Τιμή επιστροφής

Νέα παρουσία πλέγματος με συμπαγή χρήση μνήμης

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


