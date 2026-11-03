---
title: "Klasse License"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.License Klasse. Stellt Methoden bereit, um die Komponente zu lizenzieren."
type: docs
weight: 1610
url: /de/net/aspose.threed/license/
---
## License class

Stellt Methoden bereit, um die Komponente zu lizenzieren.

```csharp
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | Lizenziert die Komponente. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | Lizenziert die Komponente. |

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei namens MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

die Komponenten‑Jar‑Datei:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Siehe auch

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


