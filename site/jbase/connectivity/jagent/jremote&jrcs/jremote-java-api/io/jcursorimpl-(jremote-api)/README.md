# JCursorImpl (jremote API)

<PageHeader />

## Class JCursorImpl

All Implemented Interfaces:[JCursor](./../../jcursor-(jremote-api) "interface in com.jbase.jremote"), [JSelectList](./../../jselectlist-(jremote-api) "interface in com.jbase.jremote"), Iterable&lt;String&gt;
* * *


```
public class JCursorImpl
extends JSelectListImpl
implements JCursor
```

A cursor to a jBASE file.
This object represents a list of jBASE file records.

### Field Summary

- Fields inherited from class com.jbase.jremote.io.JSelectListImpl
    - `connection, cursorStartPos, data, FETCH_BACKWARD, FETCH_FORWARD, fetchSize`






### Constructor Summary


| Constructor and Description<br> |
| --- |
| `JCursorImpl(AbstractJRemoteConnection connection, JSelectListProt data)`<br>Constructs a cursor from a serializable select list.<br> |






### Method Summary


| Modifier and Type<br> | Method and Description<br> |
| --- | --- |
| `void`<br> | `close()`<br>Close cursor.<br> |
| `JDynArray`<br> | `getRecord()`<br>Returns the current record.<br> |
| `boolean`<br> | `hasNext()`<br>Returns whether it is possible to move the cursor forwards.<br> |
| `boolean`<br> | `hasPrevious()`<br>Returns whether it is possible to move the cursor backwards.<br> |
| `boolean`<br> | `next()`<br>Move cursor to next item<br> |
| `boolean`<br> | `previous()`<br>Move cursor to previous item<br> |
| `void`<br> | `setRecord(JDynArray record)`<br>Modifies the current record.<br> |
| `void`<br> | `update()`<br>Update changes.<br> |


- Methods inherited from class com.jbase.jremote.io.JSelectListImpl
    - `fetchNext, fetchPrevious, getData, getFetchSize, getKey, getPosition, goToPosition, hasNext, hasPrevious, iterator, next, previous, setConnection, setFetchSize`
- Methods inherited from class java.lang.Object
    - `clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait`


- Methods inherited from interface com.jbase.jremote.JSelectList
    - `getFetchSize, getKey, getPosition, goToPosition, iterator, setFetchSize`
- Methods inherited from interface java.lang.Iterable
    - `forEach, spliterator`

### Constructor Detail



#### JCursorImpl

```
public JCursorImpl(AbstractJRemoteConnection connection,
                   JSelectListProt data)
```

Constructs a cursor from a serializable select list.
Parameters:`connection` - Connection handle used to fetch records from the server`data` - Serializable select list






### Method Detail



#### next

```
public boolean next()
             throws JRemoteException
```

Move cursor to next item
Specified by:`next` in interface `JSelectList`Overrides:`next` in class `JSelectListImpl`Returns:true if OK, false otherwiseThrows:`JRemoteException`See Also:[`JSelectList.next()`](./../../jselectlist-(jremote-api)#next--)


#### previous

```
public boolean previous()
                 throws JRemoteException
```

Move cursor to previous item
Specified by:`previous` in interface `JSelectList`Overrides:`previous` in class `JSelectListImpl`Returns:true if OK, false otherwiseThrows:`JRemoteException`See Also:[`JSelectList.previous()`](./../../jselectlist-(jremote-api)#previous--)


#### hasNext

```
public boolean hasNext()
                throws JRemoteException
```

Returns whether it is possible to move the cursor forwards.
Specified by:`hasNext` in interface `JSelectList`Overrides:`hasNext` in class `JSelectListImpl`Returns:true if YES, false otherwiseThrows:`JRemoteException`See Also:[`JSelectList.hasNext()`](./../../jselectlist-(jremote-api)#hasNext--)


#### hasPrevious

```
public boolean hasPrevious()
                    throws JRemoteException
```

Returns whether it is possible to move the cursor backwards.
Specified by:`hasPrevious` in interface `JSelectList`Overrides:`hasPrevious` in class `JSelectListImpl`Returns:true if YES, false otherwiseThrows:`JRemoteException`See Also:[`JSelectList.hasPrevious()`](./../../jselectlist-(jremote-api)#hasPrevious--)

#### close

```
public void close()
           throws JRemoteException
```

Close cursor. Applies all pending changes and request the server to release all resources associated to this cursor.
Specified by:`close` in interface `JSelectList`Overrides:`close` in class `JSelectListImpl`Throws:`JRemoteException`See Also:[`JSelectList.close()`](./../../jselectlist-(jremote-api)#close--)



#### getRecord

```
public JDynArray getRecord()
```

Description copied from interface: `JCursor`

Returns the current record.
Specified by:`getRecord` in interface `JCursor`Returns:record valueSee Also:[`JCursor.getRecord()`](./../../jcursor-(jremote-api)#getRecord--)


#### setRecord

```
public void setRecord(JDynArray record)
```

Description copied from interface: `JCursor`

Modifies the current record. Changes are not applied until methods update() or close() are called.
Specified by:`setRecord` in interface `JCursor`See Also:[`JCursor.setRecord(com.jbase.jremote.JDynArray)`](./../../jcursor-(jremote-api)#setRecord-com.jbase.jremote)

#### update

```
public void update()
            throws JRemoteException
```

Description copied from interface: `JCursor`

Update changes. This method will apply all pending changes to the cursor.
Specified by:`update` in interface `JCursor`Throws:`JRemoteException`See Also:[`JCursor.update()`](./../../jcursor-(jremote-api)#update--)



Back to [jRemote API](../../../../jremote-api/README.md)

  
<PageFooter />
