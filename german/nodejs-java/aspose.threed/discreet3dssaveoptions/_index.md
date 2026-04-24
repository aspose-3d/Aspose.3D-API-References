---
title: Discreet3dsSaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Speicheroptionen für 3DS-Datei.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Name | Beschreibung |
| --- | --- |
| getExportLight() | Liest oder setzt, ob alle Lichter in der Szene exportiert werden. |

 **Result:**



---


### setExportLight{#setExportLight}

| Name | Beschreibung |
| --- | --- |
| setExportLight(value) | Liest oder setzt, ob alle Lichter in der Szene exportiert werden. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Name | Beschreibung |
| --- | --- |
| getExportCamera() | Liest oder setzt, ob alle Kameras in der Szene exportiert werden. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Name | Beschreibung |
| --- | --- |
| setExportCamera(value) | Liest oder setzt, ob alle Kameras in der Szene exportiert werden. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Name | Beschreibung |
| --- | --- |
| getDuplicatedNameSeparator() | Der Trenner zwischen dem Namen eines Objekts und dem duplizierten Zähler, Standardwert ist "_". Wenn die Szene Objekte enthält, die denselben Namen verwenden, erzeugt der Aspose.3D 3DS-Exporter einen anderen Namen für das Objekt. Zum Beispiel gibt es zwei Knoten mit dem Namen "Box", der erste Knoten hat den Namen "Box", und der zweite Knoten erhält mit der Standardkonfiguration den neuen Namen "Box_2". |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Name | Beschreibung |
| --- | --- |
| setDuplicatedNameSeparator(value) | Der Trenner zwischen dem Namen eines Objekts und dem duplizierten Zähler, Standardwert ist "_". Wenn die Szene Objekte enthält, die denselben Namen verwenden, erzeugt der Aspose.3D 3DS-Exporter einen anderen Namen für das Objekt. Zum Beispiel gibt es zwei Knoten mit dem Namen "Box", der erste Knoten hat den Namen "Box", und der zweite Knoten erhält mit der Standardkonfiguration den neuen Namen "Box_2". |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Name | Beschreibung |
| --- | --- |
| getDuplicatedNameCounterBase() | Der Zähler, der zum Erzeugen neuer Namen für duplizierte Namen verwendet wird, Standardwert ist 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Name | Beschreibung |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Der Zähler, der zum Erzeugen neuer Namen für duplizierte Namen verwendet wird, Standardwert ist 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Name | Beschreibung |
| --- | --- |
| getDuplicatedNameCounterFormat() | Das Format des duplizierten Zählers, Standardwert ist ein leerer String. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Name | Beschreibung |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Das Format des duplizierten Zählers, Standardwert ist ein leerer String. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Name | Beschreibung |
| --- | --- |
| getMasterScale() | Liest oder setzt die beim Export verwendete Master-Skala. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Name | Beschreibung |
| --- | --- |
| setMasterScale(value) | Liest oder setzt die beim Export verwendete Master-Skala. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Name | Beschreibung |
| --- | --- |
| getGammaCorrectedColor() | Eine 3ds-Datei kann originale Farbe und gamma‑korrigierte Farbe für dasselbe Attribut enthalten. Wird dies auf true gesetzt, wird nach Möglichkeit die gamma‑korrigierte Farbe verwendet, andernfalls versucht Aspose.3D, die originale Farbe zu nutzen. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Name | Beschreibung |
| --- | --- |
| setGammaCorrectedColor(value) | Eine 3ds-Datei kann originale Farbe und gamma‑korrigierte Farbe für dasselbe Attribut enthalten. Wird dies auf true gesetzt, wird nach Möglichkeit die gamma‑korrigierte Farbe verwendet, andernfalls versucht Aspose.3D, die originale Farbe zu nutzen. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Name | Beschreibung |
| --- | --- |
| getFlipCoordinateSystem() | Liest oder setzt das Umkehren des Koordinatensystems von Kontrollpunkten/Normalen beim Import/Export. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Name | Beschreibung |
| --- | --- |
| setFlipCoordinateSystem(value) | Liest oder setzt das Umkehren des Koordinatensystems von Kontrollpunkten/Normalen beim Import/Export. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Name | Beschreibung |
| --- | --- |
| getHighPreciseColor() | Wenn dies true ist, verwendet die erzeugte 3ds‑Datei hochpräzise Farben, d. h. jeder Rot‑/Grün‑/Blau‑Kanal ist ein 32‑Bit‑Float. Andernfalls verwendet die erzeugte Datei 24‑Bit‑Farben, wobei jeder Kanal ein 8‑Bit‑Byte nutzt. Der Standardwert ist false, da nicht alle Anwendungen hochpräzise Farben unterstützen. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Name | Beschreibung |
| --- | --- |
| setHighPreciseColor(value) | Wenn dies true ist, verwendet die erzeugte 3ds‑Datei hochpräzise Farben, d. h. jeder Rot‑/Grün‑/Blau‑Kanal ist ein 32‑Bit‑Float. Andernfalls verwendet die erzeugte Datei 24‑Bit‑Farben, wobei jeder Kanal ein 8‑Bit‑Byte nutzt. Der Standardwert ist false, da nicht alle Anwendungen hochpräzise Farben unterstützen. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Name | Beschreibung |
| --- | --- |
| getExportTextures() | Versucht, im Szene verwendete Texturen in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Name | Beschreibung |
| --- | --- |
| setExportTextures(value) | Versucht, im Szene verwendete Texturen in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Name | Beschreibung |
| --- | --- |
| getFileFormat() | Liefert das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |

 **Result:**



---


### getEncoding{#getEncoding}

| Name | Beschreibung |
| --- | --- |
| getEncoding() | Liest oder setzt die Standardkodierung für textbasierte Dateien. Standardwert ist null, was bedeutet, dass der Importer/Exporter entscheidet, welche Kodierung verwendet wird. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Name | Beschreibung |
| --- | --- |
| getFileSystem() | Erlaubt dem Benutzer zu bestimmen, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Name | Beschreibung |
| --- | --- |
| setFileSystem(value) | Erlaubt dem Benutzer zu bestimmen, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Name | Beschreibung |
| --- | --- |
| getLookupPaths() | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

 **Result:**



---


### getFileName{#getFileName}

| Name | Beschreibung |
| --- | --- |
| getFileName() | Der Dateiname der exportierenden/ importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Name | Beschreibung |
| --- | --- |
| setFileName(value) | Der Dateiname der exportierenden/ importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |

 **Result:**



---



