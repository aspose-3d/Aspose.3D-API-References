---
title: "Szene"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/scene/
---
## Scene class

Eine Szene ist ein Top-Level-Objekt, das die Knoten, Geometrien, Materialien, Texturen, Animationen, Posen, Unterszenen usw. enthält.  Eine Szene kann Unterszenen haben und dient als Mehrdokumentenunterstützung in Dateien wie collada/blender/fbx.  Auf die Knotenhierarchie kann über RootNodeLibrary zugegriffen werden, die verwendet wird, um während der Serialisierung (wie Metadaten oder benutzerdefinierte Objekte) eine Referenz zu nicht angehängten Objekten zu behalten, sodass sie als Bibliothek genutzt werden kann.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(entity) | Initialisiert eine neue Instanz der Klasse Scene mit einer an einen neuen Knoten angehängten Entität. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die anfängliche Entität, die an die Szene angehängt wird |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(parentScene, name) | Initialisiert eine neue Instanz der Klasse Scene als Unterszene. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| parentScene | Szene | Die übergeordnete Szene. |
| name | String | Name der Szene. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(fileName) | Initialisiert eine neue Instanz der Scene-Klasse und öffnet die Datei sofort. Dies ist ein veralteter Konstruktor, bitte verwenden Sie #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Name der zu öffnenden Datei. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Name | Beschreibung |
| --- | --- |
| getSubScenes() | Gibt alle Unter‑Szenen zurück. |

 **Result:**



---


### getLibrary{#getLibrary}

| Name | Beschreibung |
| --- | --- |
| getLibrary() | Objekte, die nicht direkt in der Szenenhierarchie verwendet werden, können in der Bibliothek definiert werden. Dies ist nützlich, wenn Sie Unter‑Szenen verwenden und wiederverwendbare Komponenten unter Unter‑Szenen ablegen. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Name | Beschreibung |
| --- | --- |
| getAnimationClips() | Gibt alle in der Szene definierten AnimationClips zurück. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Name | Beschreibung |
| --- | --- |
| getCurrentAnimationClip() | Liest oder setzt den aktiven AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Name | Beschreibung |
| --- | --- |
| setCurrentAnimationClip(value) | Liest oder setzt den aktiven AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Name | Beschreibung |
| --- | --- |
| getAssetInfo() | Liest oder setzt die übergeordnete Asset-Information, die Dokumentinformationen. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Name | Beschreibung |
| --- | --- |
| setAssetInfo(value) | Liest oder setzt die übergeordnete Asset-Information, die Dokumentinformationen. |

 **Result:**



---


### getPoses{#getPoses}

| Name | Beschreibung |
| --- | --- |
| getPoses() | Gibt alle in dieser Szene verwendeten Posen zurück. Die Posen. |

 **Result:**



---


### getRootNode{#getRootNode}

| Name | Beschreibung |
| --- | --- |
| getRootNode() | Gibt den Wurzelknoten der Szene zurück. Der Wurzelknoten. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Ruft die Szene ab, zu der dieses Objekt gehört |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Name | Beschreibung |
| --- | --- |
| getAnimationClip(name) | Gibt einen benannten AnimationClip zurück |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der |

 **Result:**
AnimationClip


---


### clear{#clear}

| Name | Beschreibung |
| --- | --- |
| clear() | Löscht den Szeneninhalt und stellt die Standardeinstellungen wieder her. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Name | Beschreibung |
| --- | --- |
| createAnimationClip(name) | Eine Kurzschreibfunktion zum Erstellen und Registrieren des AnimationClips. Der erste AnimationClip wird dem CurrentAnimationClip zugewiesen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name des Animationsclips |

 **Result:**
AnimationClip


---


### open{#open}

| Name | Beschreibung |
| --- | --- |
| open(fileName, options) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Optionen | LoadOptions | Detailliertere Konfiguration zum Öffnen des Streams. |

 **Result:**
AnimationClip


---


### open{#open}

| Name | Beschreibung |
| --- | --- |
| open(fileName) | Öffnet die Szene vom angegebenen Pfad |

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
| fromFile(fileName) | Öffnet die Szene vom angegebenen Pfad |

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
| save(fileName) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

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
| save(fileName, format) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

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
| save(fileName, options) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Optionen | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName) | Rendert die Szene in eine externe Datei aus der Sicht der angegebenen Kamera. Die Standardausgabegröße ist 1024x768 und das Ausgabeformat ist png. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName, size, format) | Rendert die Szene in eine externe Datei aus der Sicht der angegebenen Kamera. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des final gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, fileName, size, format, options) | Rendert die Szene in eine externe Datei aus der Sicht der angegebenen Kamera. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des final gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |
| Optionen | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, bitmap) | Rendern Sie die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |

 **Result:**
AnimationClip


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(camera, bitmap, options) | Rendern Sie die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |
| Optionen | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

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
| Eigenschaft | Eigenschaft | Welche Eigenschaft entfernt werden soll |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt die angegebene Eigenschaft, die durch den Namen identifiziert wird. |

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
| getProperty(property) | Rufe den Wert der angegebenen Eigenschaft ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| value | Objekt | Der Wert der Eigenschaft |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Eigenschaft


---



