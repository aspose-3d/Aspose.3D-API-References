---
title: "Klass CenterLineProfile"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Profiles.CenterLineProfile-klass. IFC-kompatibel mittlinjeprofil"
type: docs
weight: 1690
url: /sv/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC-kompatibel mittlinjeprofil

```csharp
public class CenterLineProfile : Profile
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | Skapar en ny `CenterLineProfile` med angiven kurva som mittlinje. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | Mittlinjekurvan för profilen |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Hämtar eller anger om detta objekt ska exkluderas vid export. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer detta objekt att frikopplas från andra föräldranoder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Hämtar alla föräldranoder, ett objekt kan fästas vid flera föräldranoder för geometrisk instansering |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Hämtar scenen som detta objekt tillhör |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | Tjocklek applicerad längs mittlinjen |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Hämta värdet för den angivna egenskapen |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Ta bort den angivna egenskapen identifierad med namn |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sätter värdet för den angivna egenskapen |

### Se även

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


