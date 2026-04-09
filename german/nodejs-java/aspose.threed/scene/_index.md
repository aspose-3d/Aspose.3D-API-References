---
title: Szene
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/scene/
---
## Scene class

Eine Szene ist ein Top-Level-Objekt, das die Nodes, Geometrien, Materialien, Texturen, Animationen, Posen, Unterszenen usw. enthält.  Eine Szene kann Unterszenen haben und dient als Mehrdokumentenunterstützung in Dateien wie collada/blender/fbx.  Auf die Node-Hierarchie kann über RootNodeLibrary zugegriffen werden, die verwendet wird, um während der Serialisierung (wie Metadaten oder benutzerdefinierte Objekte) einen Verweis auf nicht angehängte Objekte zu behalten, sodass sie als Bibliothek genutzt werden kann.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Scene-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| Konstruktor_Überladung(entity) | Initialisiert eine neue Instanz der Scene-Klasse mit einer an einen neuen Knoten angehängten Entität. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Die anfängliche Entität, die an die Szene angehängt wurde |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| Konstruktor_Überladung2(parentScene, name) | Initialisiert eine neue Instanz der Scene-Klasse als Unterszene. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| parentScene | Szene | Die übergeordnete Szene. |
| Name | String | Name der Szene. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| Konstruktor_Überladung3(fileName) | Initialisiert eine neue Instanz der Scene-Klasse und öffnet die Datei sofort. Dies ist ein veralteter Konstruktor, bitte verwenden Sie #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Name der zu öffnenden Datei. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Name | Beschreibung |
| --- | --- |
| getSubScenes() | Gibt alle Unterszenen zurück. |

 **Result:**



---


### getLibrary{#getLibrary}

| Name | Beschreibung |
| --- | --- |
| getLibrary() | Objekte, die nicht direkt in der Szenenhierarchie verwendet werden, können in der Bibliothek definiert werden. Dies ist nützlich, wenn Sie Unterszenen verwenden und wiederverwendbare Komponenten unter Unterszenen ablegen. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Name | Beschreibung |
| --- | --- |
| getAnimationClips() | Gibt alle in der Szene definierten AnimationClip zurück. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Name | Beschreibung |
| --- | --- |
| getCurrentAnimationClip() | Liest oder setzt das aktive AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Name | Beschreibung |
| --- | --- |
| setCurrentAnimationClip(value) | Liest oder setzt das aktive AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Name | Beschreibung |
| --- | --- |
| getAssetInfo() | Liest oder setzt die Asset-Informationen auf höchster Ebene. Die Dokumentinformationen. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Name | Beschreibung |
| --- | --- |
| setAssetInfo(value) | Liest oder setzt die Asset-Informationen auf höchster Ebene. Die Dokumentinformationen. |

 **Result:**



---


### getPoses{#getPoses}

| Name | Beschreibung |
| --- | --- |
| getPoses() | Liest alle in dieser Szene verwendeten Posen. Die Posen. |

 **Result:**



---


### getRootNode{#getRootNode}

| Name | Beschreibung |
| --- | --- |
| getRootNode() | Liest den Wurzelknoten der Szene. Der Wurzelknoten. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Liefert die Szene, zu der dieses Objekt gehört |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Name | Beschreibung |
| --- | --- |
| getAnimationClip(name) | Liest ein benanntes AnimationClip |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der |

 **Result:**
AnimationClip


---


### clear{#clear}

| Name | Beschreibung |
| --- | --- |
| clear() | Löscht den Inhalt der Szene und stellt die Standardeinstellungen wieder her. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Name | Beschreibung |
| --- | --- |
| createAnimationClip(name) | Eine Kurzschreibweise-Funktion zum Erstellen und Registrieren des AnimationClip. Das erste AnimationClip wird dem CurrentAnimationClip zugewiesen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name des Animationsclips |

 **Result:**
AnimationClip


---


### open{#open}

| Name | Beschreibung |
| --- | --- |
| open(fileName, options) | Öffnet die Szene aus dem angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | LoadOptions | Detailliertere Konfiguration zum Öffnen des Streams. |

 **Result:**
AnimationClip


---


### open{#open}

| Name | Beschreibung |
| --- | --- |
| open(fileName) | Öffnet die Szene aus dem angegebenen Pfad. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Name | Beschreibung |
| --- | --- |
| fromFile(fileName) | Öffnet die Szene aus dem angegebenen Pfad. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |

 **Result:**
AnimationClip


---


### save{#save}

| Name | Beschreibung |
| --- | --- |
| save(fileName) | Speichert die Szene im angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |

 **Result:**
AnimationClip


---


### save{#save}

| Name | Beschreibung |
| --- | --- |
| save(fileName, format) | Speichert die Szene im angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Format | FileFormat | Format. |

 **Result:**
AnimationClip


---


### save{#save}

| Name | Beschreibung |
| --- | --- |
| save(fileName, options) | Speichert die Szene im angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName) | Rendern Sie die Szene aus der angegebenen Kameraperspektive in eine externe Datei. Die Standardausgabegröße beträgt 1024 × 768 und das Ausgabeformat ist PNG |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| camera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName, size, format) | Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| camera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des finalen gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName, size, format, options) | Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| camera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des finalen gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |
| options | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, bitmap) | Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| camera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, bitmap, options) | Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| camera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |
| options | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

 **Result:**
AnimationClip


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt eine dynamische Eigenschaft. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | Property | Welche Eigenschaft zu entfernen ist |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entferne die angegebene Eigenschaft, die durch ihren Namen identifiziert wird |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty(property) | Liefere den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Object


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| Wert | Object | Der Wert der Eigenschaft |

 **Result:**
Object


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Property


---



