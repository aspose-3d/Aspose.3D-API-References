---
title: ShaderTechnique
second_title: Aspose.3D for Java API リファレンス
description: シェーダーテクニックは、具体的なレンダリング実装を表します。
type: docs
weight: 169
url: /ja/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

シェーダーテクニックは、具体的なレンダリング実装を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | 新しい [ShaderTechnique](../../com.aspose.threed/shadertechnique) クラスのインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | 動的プロパティをシェーダパラメータにバインドします |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | このテクニックの説明を取得します |
| [getRenderAPI()](#getRenderAPI--) | このテクニックで使用されるレンダリングAPIを取得します |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | レンダリングAPIのバージョンを取得します。 |
| [getShaderContent()](#getShaderContent--) | 埋め込みシェーダスクリプトの内容を取得します。 |
| [getShaderEntry()](#getShaderEntry--) | シェーダのエントリーポイントを取得します。HLSL のようなシェーダはカスタマイズされたエントリを持つことがあります。 |
| [getShaderFile()](#getShaderFile--) | 外部シェーダファイルのファイル名を取得します。 |
| [getShaderLanguage()](#getShaderLanguage--) | このテクニックで使用されるシェーダ言語を取得します。 |
| [getShaderParameters()](#getShaderParameters--) | シェーダパラメータの定義を取得します。 |
| [getShaderVersion()](#getShaderVersion--) | このテクニックで使用されるシェーダーバージョンを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | このテクニックの説明を設定します |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | このテクニックで使用されるレンダリング API を設定します |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | レンダリング API のバージョンを設定します。 |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | 埋め込みシェーダースクリプトの内容を設定します。 |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | シェーダーのエントリーポイントを設定します。HLSL のようなシェーダーはカスタマイズされたエントリを持つことができます。 |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | 外部シェーダーファイルのファイル名を設定します。 |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | このテクニックで使用されるシェーダー言語を設定します。 |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | このテクニックで使用されるシェーダーバージョンを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


新しい [ShaderTechnique](../../com.aspose.threed/shadertechnique) クラスのインスタンスを初期化します。

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


動的プロパティをシェーダパラメータにバインドします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 動的プロパティの名前です。 |
| shaderParameter | java.lang.String | シェーダーパラメータの名前です。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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
### getDescription() {#getDescription--}
```
public String getDescription()
```


このテクニックの説明を取得します

**Returns:**
java.lang.String - このテクニックの説明
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


このテクニックで使用されるレンダリングAPIを取得します

**Returns:**
java.lang.String - このテクニックで使用されるレンダリング API
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


レンダリングAPIのバージョンを取得します。

**Returns:**
java.lang.String - レンダリング API のバージョンです。
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


埋め込みシェーダースクリプトの内容を取得します。HLSL/GLSL シェーダーのソースファイルである可能性があります。

**Returns:**
byte[] - 埋め込みシェーダースクリプトの内容です。HLSL/GLSL シェーダーのソースファイルである可能性があります。
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


シェーダのエントリーポイントを取得します。HLSL のようなシェーダはカスタマイズされたエントリを持つことがあります。

**Returns:**
java.lang.String - シェーダーのエントリーポイントです。HLSL のようなシェーダーはカスタマイズされたエントリを持つことができます。
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


外部シェーダファイルのファイル名を取得します。

**Returns:**
java.lang.String - 外部シェーダーファイルのファイル名です。
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


このテクニックで使用されるシェーダ言語を取得します。

**Returns:**
java.lang.String - このテクニックで使用されるシェーダー言語です。
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


シェーダーパラメータ定義を取得します。キーは動的プロパティの名前で、値はプロパティが接続されているシェーダーパラメータの名前です。

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - シェーダーパラメータ定義です。キーは動的プロパティの名前で、値はプロパティが接続されているシェーダーパラメータの名前です。
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


このテクニックで使用されるシェーダーバージョンを取得します。

**Returns:**
java.lang.String - このテクニックで使用されるシェーダーバージョンです。
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


このテクニックの説明を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


このテクニックで使用されるレンダリング API を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


レンダリング API のバージョンを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


埋め込みシェーダースクリプトの内容を設定します。HLSL/GLSL シェーダーのソースファイルである可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | byte[] | 新しい値 |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


シェーダーのエントリーポイントを設定します。HLSL のようなシェーダーはカスタマイズされたエントリを持つことができます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


外部シェーダーファイルのファイル名を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


このテクニックで使用されるシェーダー言語を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


このテクニックで使用されるシェーダーバージョンを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

