---
title: MappingMode
second_title: Aspose.3D voor .NET API-referentie
description: Bepaalt hoe het element wordt toegewezen aan een oppervlak. DeMappingMode./mappingmode/ gedefinieerd hoeVertexElement./vertexelement/ wordt toegewezen aan het oppervlak van de geometrie.
type: docs
weight: 440
url: /nl/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

Bepaalt hoe het element wordt toegewezen aan een oppervlak. De`MappingMode` gedefinieerd hoe[`VertexElement`](../vertexelement/) wordt toegewezen aan het oppervlak van de geometrie.

```csharp
public enum MappingMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ControlPoint | `0` | Alle gegevens worden toegewezen aan het controlepunt van de geometrie. |
| PolygonVertex | `1` | De gegevens worden toegewezen aan het hoekpunt van de polygoon Wanneer een controlepunt wordt gedeeld door meerdere polygonen en de gegevens worden toegewezen alsPolygonVertex zal het controlepunt als verschillende polygoon vertex hun eigen data hebben |
| Polygon | `2` | De gegevens worden toegewezen aan de polygoon. Elk hoekpunt van de polygoon deelt dezelfde gegevens wanneer de mappingmodus isPolygon . |
| Edge | `3` | De gegevens worden toegewezen aan de rand. Elk eindpunt van de rand deelt dezelfde gegevens wanneer de toewijzingEdge . |
| AllSame | `4` | Eén gegevens toegewezen aan het hele oppervlak. Welke gegevens dan ook worden geïnterpreteerd als controlepunt/polygoonvertex/randeindpunten, de gegevens zijn altijd dezelfde als gedefinieerd doorAllSame . |

### Zie ook

* naamruimte [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
