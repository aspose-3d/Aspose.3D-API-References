---
title: PdfSaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

Die Speicheroptionen beim PDF‑Export.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| Name | Beschreibung |
| --- | --- |
| getRenderMode() | Der Rendermodus gibt den Stil an, in dem das 3D‑Werk gerendert wird. Der Wert der Eigenschaft ist die Ganzzahlkonstante PdfRenderMode. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| Name | Beschreibung |
| --- | --- |
| setRenderMode(value) | Der Rendermodus gibt den Stil an, in dem das 3D‑Werk gerendert wird. Der Wert der Eigenschaft ist die Ganzzahlkonstante PdfRenderMode. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| Name | Beschreibung |
| --- | --- |
| getLightingScheme() | LightingScheme gibt die Beleuchtung an, die auf das 3D‑Werk angewendet wird. Der Wert der Eigenschaft ist die Ganzzahlkonstante PdfLightingScheme. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| Name | Beschreibung |
| --- | --- |
| setLightingScheme(value) | LightingScheme gibt die Beleuchtung an, die auf das 3D‑Werk angewendet wird. Der Wert der Eigenschaft ist die Ganzzahlkonstante PdfLightingScheme. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Name | Beschreibung |
| --- | --- |
| getBackgroundColor() | Hintergrundfarbe der 3D-Ansicht in der PDF-Datei. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Name | Beschreibung |
| --- | --- |
| setBackgroundColor(value) | Hintergrundfarbe der 3D-Ansicht in der PDF-Datei. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| Name | Beschreibung |
| --- | --- |
| getFaceColor() | Liest oder setzt die Gesichtsfarbe, die beim Rendern des 3D-Inhalts verwendet wird. Dies ist nur relevant, wenn der RenderMode den Wert Illustration hat. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| Name | Beschreibung |
| --- | --- |
| setFaceColor(value) | Liest oder setzt die Gesichtsfarbe, die beim Rendern des 3D-Inhalts verwendet wird. Dies ist nur relevant, wenn der RenderMode den Wert Illustration hat. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| Name | Beschreibung |
| --- | --- |
| getAuxiliaryColor() | Liest oder setzt die Hilfsfarbe, die beim Rendern des 3D-Inhalts verwendet wird. Die Interpretation dieser Farbe hängt vom RenderMode ab. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| Name | Beschreibung |
| --- | --- |
| setAuxiliaryColor(value) | Liest oder setzt die Hilfsfarbe, die beim Rendern des 3D-Inhalts verwendet wird. Die Interpretation dieser Farbe hängt vom RenderMode ab. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Name | Beschreibung |
| --- | --- |
| getFlipCoordinateSystem() | Liest oder setzt, ob das Koordinatensystem der Szene beim Export umgekehrt wird. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Name | Beschreibung |
| --- | --- |
| setFlipCoordinateSystem(value) | Liest oder setzt, ob das Koordinatensystem der Szene beim Export umgekehrt wird. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Name | Beschreibung |
| --- | --- |
| getEmbedTextures() | Betten Sie die externen Texturen in die PDF-Datei ein, der Standardwert ist false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Name | Beschreibung |
| --- | --- |
| setEmbedTextures(value) | Betten Sie die externen Texturen in die PDF-Datei ein, der Standardwert ist false. |

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



