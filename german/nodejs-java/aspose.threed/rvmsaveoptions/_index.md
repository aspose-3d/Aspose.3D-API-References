---
title: "RvmSaveOptions"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Speicheroptionen für die Aveva PDMS RVM-Datei.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(contentType) | Konstruktor von RvmSaveOptions |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Name | Beschreibung |
| --- | --- |
| getFileNote() | Dateikommentar im Dateikopf. |

 **Result:**



---


### setFileNote{#setFileNote}

| Name | Beschreibung |
| --- | --- |
| setFileNote(value) | Dateikommentar im Dateikopf. |

 **Result:**



---


### getAuthor{#getAuthor}

| Name | Beschreibung |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Name | Beschreibung |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Name | Beschreibung |
| --- | --- |
| getCreationTime() | Der Zeitstempel, der diese Datei exportierte, Standardwert ist die aktuelle Zeit. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Name | Beschreibung |
| --- | --- |
| setCreationTime(value) | Der Zeitstempel, der diese Datei exportierte, Standardwert ist die aktuelle Zeit. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Name | Beschreibung |
| --- | --- |
| getAttributePrefix() | Liest oder setzt das Präfix der Attribute, die exportiert werden sollen; die exportierte Eigenschaft enthält kein Präfix, benutzerdefinierte Eigenschaften mit anderem Präfix werden nicht exportiert, Standardwert ist 'rvm:'. Zum Beispiel, wenn eine Eigenschaft rvm:Refno=345 ist, wird das exportierte Attribut Refno = 345 sein, das Präfix wird entfernt. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Name | Beschreibung |
| --- | --- |
| setAttributePrefix(value) | Liest oder setzt das Präfix der Attribute, die exportiert werden sollen; die exportierte Eigenschaft enthält kein Präfix, benutzerdefinierte Eigenschaften mit anderem Präfix werden nicht exportiert, Standardwert ist 'rvm:'. Zum Beispiel, wenn eine Eigenschaft rvm:Refno=345 ist, wird das exportierte Attribut Refno = 345 sein, das Präfix wird entfernt. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Name | Beschreibung |
| --- | --- |
| getAttributeListFile() | Liest oder setzt den Dateinamen der Attributlisten-Datei; der Exporter erzeugt einen Namen basierend auf dem .rvm-Dateinamen, wenn diese Eigenschaft nicht definiert ist, Standardwert ist null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Name | Beschreibung |
| --- | --- |
| setAttributeListFile(value) | Liest oder setzt den Dateinamen der Attributlisten-Datei; der Exporter erzeugt einen Namen basierend auf dem .rvm-Dateinamen, wenn diese Eigenschaft nicht definiert ist, Standardwert ist null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Name | Beschreibung |
| --- | --- |
| getExportAttributes() | Liest oder setzt, ob die Attributliste in eine externe .att-Datei exportiert werden soll, Standardwert ist false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Name | Beschreibung |
| --- | --- |
| setExportAttributes(value) | Liest oder setzt, ob die Attributliste in eine externe .att-Datei exportiert werden soll, Standardwert ist false. |

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



