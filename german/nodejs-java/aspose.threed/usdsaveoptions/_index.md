---
title: UsdSaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Speicheroptionen für USD/USDZ-Formate.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert ein neues UsdSaveOptions mit dem Format FileFormat.USD. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(fileFormat) | Initialisiert ein neues UsdSaveOptions mit dem angegebenen USD/USDZ-Format. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Name | Beschreibung |
| --- | --- |
| getPrimitiveToMesh() | Konvertiere die primitiven Entitäten während des Exports in ein Mesh. Oder kodiere die Primitiven direkt in die Ausgabedatei (verwendet die Erweiterungsdefinition von Aspose für inoffizielle Primitive wie Dish, Torus). Standardwert ist true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Name | Beschreibung |
| --- | --- |
| setPrimitiveToMesh(value) | Konvertiere die primitiven Entitäten während des Exports in ein Mesh. Oder kodiere die Primitiven direkt in die Ausgabedatei (verwendet die Erweiterungsdefinition von Aspose für inoffizielle Primitive wie Dish, Torus). Standardwert ist true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Name | Beschreibung |
| --- | --- |
| getExportMetaData() | Exportiere die Eigenschaften des Knotens über das customData-Feld von USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Name | Beschreibung |
| --- | --- |
| setExportMetaData(value) | Exportiere die Eigenschaften des Knotens über das customData-Feld von USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| getMaterialConverter() | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der USD-Exporter das Standardmaterial automatisch in ein PBR-Material. Standardwert ist null. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| setMaterialConverter(value) | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der USD-Exporter das Standardmaterial automatisch in ein PBR-Material. Standardwert ist null. |

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



