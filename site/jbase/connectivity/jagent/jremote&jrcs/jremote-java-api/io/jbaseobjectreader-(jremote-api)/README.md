# JBaseObjectReader (jremote API)

<PageHeader />

## Interface JBaseObjectReader

All Known Implementing Classes:[AbstractJBaseObjectReader](./../abstractjbaseobjectwriter-(jremote-api) "class in com.jbase.jremote.io"), [IOJBaseObjectReader](./../iojbaseobjectreader-(jremote-api) "class in com.jbase.jremote.io"), [NIOJBaseObjectReader](./../niojbaseobjectreader-(jremote-api) "class in com.jbase.jremote.io")
* * *


```
public interface JBaseObjectReader
```

Deserializes objects sent from the jsqld server. Clients of classes implementing this interface use readObject method to read deserialized objects. This interface is simillar to java.io.ObjectInputStream. It does not extend java.io.ObjectInputStream because that would require handling of the original Java'a serialization protocol on the jsqld server.

### Method Summary


| Modifier and Type<br> | Method and Description<br> |
| --- | --- |
| `void`<br> | `close()` <br> |
| `byte[]`<br> | `readBytes()` <br> |
| `int`<br> | `readInt()`<br>Reads a 32 bits integer from the underlying InputStream.<br> |
| `Object`<br> | `readObject()`<br>Reads/deserializes next object.<br> |
| `IByteObject`<br> | `readObject(IByteObject o)`<br>Reads/deserializes next byte object, a new IByteObject should be created and returned if a null argument is passed in.<br> |
| `JBaseSerializable`<br> | `readObject(JBaseSerializable o)`<br>Reads/deserializes next object, a JBaseSerializable object should be created and returned if a null argument is passed in.<br> |
| `JBaseSerializable`<br> | `readRootObject()`<br>Deserializes a root object.<br> |
| `String`<br> | `readString()`<br>Reads a java.lang.String.<br> |

### Method Detail

#### readObject

```
Object readObject()
           throws IOException,
                  ClassNotFoundException
```

Reads/deserializes next object. Client should use Java safe cast to cast the object to an expected type.
Throws:`IOException``ClassNotFoundException`
#### 


#### readObject

```
JBaseSerializable readObject(JBaseSerializable o)
                      throws IOException,
                             ClassNotFoundException
```

Reads/deserializes next object, a JBaseSerializable object should be created and returned if a null argument is passed in.
Throws:`IOException``ClassNotFoundException`
#### 


#### readObject

```
IByteObject readObject(IByteObject o)
                throws IOException
```

Reads/deserializes next byte object, a new IByteObject should be created and returned if a null argument is passed in.
Throws:`IOException`
#### 


#### readInt

```
int readInt()
     throws IOException
```

Reads a 32 bits integer from the underlying InputStream.
Throws:`IOException`
#### 


#### readString

```
String readString()
           throws IOException
```

Reads a java.lang.String. This method will deserialize and convert to String a JDynArray (a variable of type CVar serialized on the server). It will throw an exception if the object coming from the server is of any other type.
Throws:`IOException`
#### 


#### readBytes

```
byte[] readBytes()
          throws IOException
```
Throws:`IOException`
#### 


#### readRootObject

```
JBaseSerializable readRootObject()
                          throws IOException,
                                 ClassNotFoundException
```

Deserializes a root object. This method must not be used by implementors of JBaseSerializable (in readObject).
Returns:an instance of JBaseSerializableThrows:`IOException``ClassNotFoundException`
#### 


#### close

```
void close()
    throws IOException
```
Throws:`IOException`

Back to [jRemote API](../../../../jremote-api/README.md)

  
<PageFooter />
