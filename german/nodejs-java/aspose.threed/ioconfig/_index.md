---
title: IOConfig
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

IO-Konfiguration für Serialisierung/Deserialisierung. Der Benutzer kann detaillierte Konfigurationen wie den Abhängigkeitsnachschlagepfad oder formatbezogene Einstellungen hier angeben  @hideconstructor


## Methoden

### getFileSystemFactory{#getFileSystemFactory}

| Name | Beschreibung |
| --- | --- |
| getFileSystemFactory() | Liest oder setzt die Fabrikklasse für FileSystem. Die Standardfabrik erstellt LocalFileSystem, das für Serverumgebungen nicht geeignet ist. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Name | Beschreibung |
| --- | --- |
| setFileSystemFactory(value) | Liest oder setzt die Fabrikklasse für FileSystem. Die Standardfabrik erstellt LocalFileSystem, das für Serverumgebungen nicht geeignet ist. |

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



