---
title: Discreet3dsSaveOptions
second_title: Aspose.3D for Java API Reference
description: 3DS फ़ाइल के लिए सहेजने विकल्प।
type: docs
weight: 44
url: /hi/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

3DS फ़ाइल के लिए सहेजने विकल्प।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | डुप्लिकेट नामों के लिए नया नाम उत्पन्न करने हेतु उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है। |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | डुप्लिकेट काउंटर का प्रारूप, डिफ़ॉल्ट मान खाली स्ट्रिंग है। |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | ऑब्जेक्ट के नाम और डुप्लिकेट काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "\_" है। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportCamera()](#getExportCamera--) | दृश्य में सभी कैमरों को निर्यात करना है या नहीं, प्राप्त करता है। |
| [getExportLight()](#getExportLight--) | दृश्य में सभी लाइट्स को निर्यात करना है या नहीं, प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल का फ्लिप कोऑर्डिनेट सिस्टम प्राप्त करता है। |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | एक 3ds फ़ाइल में समान विशेषता के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true पर सेट करने से संभव होने पर गामा-सुधारित रंग उपयोग होगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने का प्रयास करेगा। |
| [getHighPreciseColor()](#getHighPreciseColor--) | यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32 बिट फ़्लोट में होगा। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getMasterScale()](#getMasterScale--) | निर्यात में उपयोग किए जाने वाले मास्टर स्केल को प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | डुप्लिकेट नामों के लिए नया नाम उत्पन्न करने हेतु उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है। |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | डुप्लिकेट काउंटर का प्रारूप, डिफ़ॉल्ट मान खाली स्ट्रिंग है। |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | ऑब्जेक्ट के नाम और डुप्लिकेट काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "\_" है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | निर्धारित करता है कि क्या दृश्य में सभी कैमरों को निर्यात किया जाए। |
| [setExportLight(boolean value)](#setExportLight-boolean-) | निर्धारित करता है कि क्या दृश्य में सभी लाइटों को निर्यात किया जाए। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल का फ्लिप कोऑर्डिनेट सिस्टम सेट करता है। |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | एक 3ds फ़ाइल में समान विशेषता के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true पर सेट करने से संभव होने पर गामा-सुधारित रंग उपयोग होगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने का प्रयास करेगा। |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32 बिट फ़्लोट में होगा। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setMasterScale(double value)](#setMasterScale-double-) | निर्यात में उपयोग किए जाने वाले मुख्य स्केल को सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


[Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) का कंस्ट्रक्टर

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


डुप्लिकेट नामों के लिए नया नाम उत्पन्न करने हेतु उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है।

**Returns:**
int - दोहराए गए नामों के लिए नया नाम उत्पन्न करने हेतु उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है।
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


डुप्लिकेट काउंटर का प्रारूप, डिफ़ॉल्ट मान खाली स्ट्रिंग है।

**Returns:**
java.lang.String - दोहराए गए काउंटर का फ़ॉर्मेट, डिफ़ॉल्ट मान खाली स्ट्रिंग है।
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


ऑब्जेक्ट के नाम और दोहराए गए काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "\_" है। जब दृश्य में ऐसे ऑब्जेक्ट होते हैं जिनका नाम समान होता है, Aspose.3D 3DS निर्यातकर्ता ऑब्जेक्ट के लिए अलग नाम उत्पन्न करेगा। उदाहरण के लिए दो नोड्स का नाम "Box" है, पहला नोड "Box" नाम रखेगा, और दूसरा नोड डिफ़ॉल्ट कॉन्फ़िगरेशन का उपयोग करके नया नाम "Box\_2" प्राप्त करेगा।

**Returns:**
ऑब्जेक्ट के नाम और दोहराए गए काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "\_" है। जब दृश्य में ऐसे ऑब्जेक्ट होते हैं जिनका नाम समान होता है, Aspose.3D 3DS निर्यातकर्ता ऑब्जेक्ट के लिए अलग नाम उत्पन्न करेगा। उदाहरण के लिए दो नोड्स का नाम "Box" है, पहला नोड "Box" नाम रखेगा, और दूसरा नोड डिफ़ॉल्ट कॉन्फ़िगरेशन का उपयोग करके नया नाम "Box\_2" प्राप्त करेगा।
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।

**Returns:**
java.nio.charset.Charset - टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


दृश्य में सभी कैमरों को निर्यात करना है या नहीं, प्राप्त करता है।

**Returns:**
boolean - क्या दृश्य में सभी कैमरों को निर्यात किया जाए।
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


दृश्य में सभी लाइट्स को निर्यात करना है या नहीं, प्राप्त करता है।

**Returns:**
boolean - क्या दृश्य में सभी लाइटों को निर्यात किया जाए।
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Returns:**
boolean - दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Returns:**
java.lang.String - एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल का फ्लिप कोऑर्डिनेट सिस्टम प्राप्त करता है।

**Returns:**
boolean - इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के कोऑर्डिनेट सिस्टम को उलटना।
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


एक 3ds फ़ाइल में समान विशेषता के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true पर सेट करने से संभव होने पर गामा-सुधारित रंग उपयोग होगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने का प्रयास करेगा।

**Returns:**
boolean - एक 3ds फ़ाइल में समान गुण के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true सेट करने पर संभव होने पर गामा-सुधारित रंग उपयोग किया जाएगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने का प्रयास करेगा।
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32‑bit फ़्लोट में होगा। अन्यथा उत्पन्न फ़ाइल 24‑bit रंग उपयोग करेगी, प्रत्येक चैनल 8‑bit बाइट में होगा। डिफ़ॉल्ट मान false है, क्योंकि सभी अनुप्रयोग उच्च‑सटीकता वाले रंग का समर्थन नहीं करते।

**Returns:**
यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32‑bit फ़्लोट में होगा। अन्यथा उत्पन्न फ़ाइल 24‑bit रंग उपयोग करेगी, प्रत्येक चैनल 8‑bit बाइट में होगा। डिफ़ॉल्ट मान false है, क्योंकि सभी अनुप्रयोग उच्च‑सटीकता वाले रंग का समर्थन नहीं करते।
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को बाहरी फ़ाइल लोड करने के लिए खोजने की अनुमति देंगे। **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


निर्यात में उपयोग किए जाने वाले मास्टर स्केल को प्राप्त करता है।

**Returns:**
double - निर्यात में उपयोग किया गया मुख्य स्केल।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


डुप्लिकेट नामों के लिए नया नाम उत्पन्न करने हेतु उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


डुप्लिकेट काउंटर का प्रारूप, डिफ़ॉल्ट मान खाली स्ट्रिंग है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


ऑब्जेक्ट के नाम और दोहराए गए काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "\_" है। जब दृश्य में ऐसे ऑब्जेक्ट होते हैं जिनका नाम समान होता है, Aspose.3D 3DS निर्यातकर्ता ऑब्जेक्ट के लिए अलग नाम उत्पन्न करेगा। उदाहरण के लिए दो नोड्स का नाम "Box" है, पहला नोड "Box" नाम रखेगा, और दूसरा नोड डिफ़ॉल्ट कॉन्फ़िगरेशन का उपयोग करके नया नाम "Box\_2" प्राप्त करेगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सी एन्कोडिंग उपयोग करनी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset | नया मान |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


निर्धारित करता है कि क्या दृश्य में सभी कैमरों को निर्यात किया जाए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


निर्धारित करता है कि क्या दृश्य में सभी लाइटों को निर्यात किया जाए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | नई मान **Example:** डिफ़ॉल्ट FileSystem LocalFileSystem है, यह सर्वर-साइड जैसे वातावरण में सुरक्षित नहीं है, लेकिन आप अलग इम्प्लीमेंटेशन निर्दिष्ट करके फ़ाइल सिस्टम एक्सेस को ओवरराइड कर सकते हैं। Aspose.3D विभिन्न FileSystem इम्प्लीमेंटेशन प्रदान करता है जैसे: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | नई मान **Example:** SaveOptions/LoadOptions में डिफ़ॉल्ट FileSystem डायरेक्टरी-आधारित फ़ाइल सिस्टम है, आप इसे IOConfig.FileSystemFactory के माध्यम से निर्दिष्ट करके डिफ़ॉल्ट इम्प्लीमेंटेशन को ओवरराइड कर सकते हैं: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल का फ्लिप कोऑर्डिनेट सिस्टम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


एक 3ds फ़ाइल में समान विशेषता के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true पर सेट करने से संभव होने पर गामा-सुधारित रंग उपयोग होगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने का प्रयास करेगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32‑bit फ़्लोट में होगा। अन्यथा उत्पन्न फ़ाइल 24‑bit रंग उपयोग करेगी, प्रत्येक चैनल 8‑bit बाइट में होगा। डिफ़ॉल्ट मान false है, क्योंकि सभी अनुप्रयोग उच्च‑सटीकता वाले रंग का समर्थन नहीं करते।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.ArrayList<java.lang.String> | नई मान **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


निर्यात में उपयोग किए जाने वाले मुख्य स्केल को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

