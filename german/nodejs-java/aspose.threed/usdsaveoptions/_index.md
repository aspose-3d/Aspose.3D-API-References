---
title: "UsdSaveOptions"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
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
| constructor() | Initialisiere ein neues UsdSaveOptions mit dem Format FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(fileFormat) | Initialisiere ein neues UsdSaveOptions mit dem angegebenen USD/USDZ-Format. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Name | Beschreibung |
| --- | --- |
| getPrimitiveToMesh() | Konvertiere die primitiven Entitäten während des Exports in ein Mesh. Oder kodieren Sie die Primitive direkt in die Ausgabedatei (verwendet Aspose's Erweiterungsdefinition für inoffizielle Primitive wie Dish, Torus). Der Standardwert ist true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Name | Beschreibung |
| --- | --- |
| setPrimitiveToMesh(value) | Konvertiere die primitiven Entitäten während des Exports in ein Mesh. Oder kodieren Sie die Primitive direkt in die Ausgabedatei (verwendet Aspose's Erweiterungsdefinition für inoffizielle Primitive wie Dish, Torus). Der Standardwert ist true. |

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
| getMaterialConverter() | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der USD-Exporter das Standardmaterial automatisch in ein PBR-Material. Der Standardwert ist null. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| setMaterialConverter(value) | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der USD-Exporter das Standardmaterial automatisch in ein PBR-Material. Der Standardwert ist null. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Name | Beschreibung |
| --- | --- |
| getExportTextures() | Versuchen Sie, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Name | Beschreibung |
| --- | --- |
| setExportTextures(value) | Versuchen Sie, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Name | Beschreibung |
| --- | --- |
| getFileFormat() | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |

 **Result:**



---


### getEncoding{#getEncoding}

| Name | Beschreibung |
| --- | --- |
| getEncoding() | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Name | Beschreibung |
| --- | --- |
| getFileSystem() | Ermöglicht dem Benutzer, zu steuern, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Name | Beschreibung |
| --- | --- |
| setFileSystem(value) | Ermöglicht dem Benutzer, zu steuern, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Name | Beschreibung |
| --- | --- |
| getLookupPaths() | Einige Dateien wie OBJ hängen von externen Dateien ab; die Suchpfade ermöglichen Aspose.3D, nach externen Dateien zum Laden zu suchen. |

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



