# Uses of Class com.jbase.jrcs.JDynArray (jrclient   API)

<PageHeader />

## Uses of [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") in [com.jbase.jrcs](./../../com.jbase.jrcs-jrclient-api)

**Methods in [com.jbase.jrcs](./../../com.jbase.jrcs-jrclient-api) that return**[**JDynArray**](./../../jdynarray-jrclient-api "class in com.jbase.jrcs")

| Modifier and Type | Method |  Description |
| --- | --- | --- |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JDynArray.[extractDA](./../../jdynarray-jrclient-api)(int amc) | Extracts the specified attribute as a dynamic array |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JDynArray.[extractDA](./../../jdynarray-jrclient-api)(int amc, int vmc) | Extracts the specified attribute or value as a dynamic array |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JDynArray.[extractDA](./../../jdynarray-jrclient-api)(int amc, int vmc, int svmc) |  Extracts the specified attribute, value or sub-value as a dynamic array |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JCommon.[getDA](./../../jcommon-jrclient-api)(int index) | Retrieves a dynamic array from a specific position in a common block |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[getIndex](./../../jfile-jrclient-api)(String indexName) | Reads information about the specified index |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JConnection.[getjBaseVersion](./../../jconnection-jrclient-api)() | Retrieves the version of jBASE database connected to this JConnection object |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[read](./../../jfile-jrclient-api)(String key) | Reads a record from the file without locking |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[read](./../../jfile-jrclient-api)(String key, boolean locked) | Reads a record from the file, optionally locking it |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[read](./../../jfile-jrclient-api)(String key, boolean locked, boolean wait) | Reads a record from the file, optionally locking it and waiting for the lock |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readNamedField](./../../jfile-jrclient-api)(String key, String field) | Reads a named field from a file record |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readNamedField](./../../jfile-jrclient-api)(String key, String field, boolean locked) | Reads a named field from a file record, optionally locking the record |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readNamedField](./../../jfile-jrclient-api)(String key, String field, boolean locked, boolean wait) |  Reads a named field from a file record, optionally locking the record |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readV](./../../jfile-jrclient-api)(String key, int attrib) | Reads an attribute from a file record without locking |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readV](./../../jfile-jrclient-api)([String](http://java.sun.com/j2se/1.5.0/docs/api/java/lang/String.html?is-external=true "class or interface in java.lang") key, int attrib, boolean locked) | Reads an attribute from a file record, optionally locking the record |
| [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") | JFile.[readV](./../../jfile-jrclient-api)(String key, int attrib, boolean locked, boolean wait) |  Reads an attribute from a file record, optionally locking the record and waiting for the lock |

**Methods in [com.jbase.jrcs](./../../com.jbase.jrcs-jrclient-api) with parameters of type**[**JDynArray**](./../../jdynarray-jrclient-api "class in com.jbase.jrcs")

| Modifier and Type | Method | Description |
| --- | --- | --- |
| void | JDynArray.[assign](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") src) | Assigns the value of a dynamic array to this dynamic array |
| void | JConnection.[call](./../../jconnection-jrclient-api)(String subName, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs")[] parms) | Calls a host-side subroutine with given parameters |
| void | JDynArray.[insert](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc) | Inserts data from the given dynamic array into the specified attribute |
| void | JDynArray.[insert](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc) | Inserts data from the given dynamic array into the specified attribute or value. |
| void | JDynArray.[insert](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc, int svmc) | Inserts data from the given dynamic array into the specified attribute, value or sub-value. |
| void | JDynArray.[insertDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc) | Inserts data from the given dynamic array into the specified attribute. |
| void | JDynArray.[insertDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc) | Inserts data from the given dynamic array into the specified attribute or value. |
| void | JDynArray.[insertDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc, int svmc) | Inserts data from the given dynamic array into the specified attribute, value or sub-value. |
| void | JDynArray.[replace](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc) | Replaces the given attribute with the content of specified dynamic array |
| void | JDynArray.[replace](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc) | Replaces the given attribute or value with the content of specified dynamic array |
| void | JDynArray.[replace](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc, int svmc) | Replaces the given attribute, value or sub-value with the content of specified dynamic array |
| void | JDynArray.[replaceDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc) | Replaces the given attribute with the content of specified dynamic array Same as replace(JDynArray, amc) |
| void | JDynArray.[replaceDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc) | Replaces the given attribute or value with the content of specified dynamic array Same as replace(JDynArray, amc, vmc) |
| void | JDynArray.[replaceDA](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int amc, int vmc, int svmc) | Replaces the given attribute, value or sub-value with the content of specified dynamic array. |
| void | JCommon.[setDA](./../../jcommon-jrclient-api)(int index, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") dynArray) | Stores a dynamic array into a specific position in a common block |
| void | JFile.[write](./../../jfile-jrclient-api)(String key, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data) | Writes a record to the file releasing the lock if there is one |
| void | JFile.[write](./../../jfile-jrclient-api)(String key, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, boolean unlock) | Writes a record to the file optionally releasing the lock |
| void | JFile.[writeNamedField](./../../jfile-jrclient-api)(String key, String field, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data) | Writes a named record field to the file |
| void | JFile.[writeNamedField](./../../jfile-jrclient-api)(String key, String field, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, boolean unlock) | Writes a named record field to the file optionally releasing the lock |
| void | JFile.[writeV](./../../jfile-jrclient-api)(String key, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int attrib) | Writes a record attribute to the file releasing the lock if there is one |
| void | JFile.[writeV](./../../jfile-jrclient-api)(String key, [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") data, int attrib, boolean unlock) | Writes a record attribute to the file optionally releasing the lock |

**Constructors in [com.jbase.jrcs](./../../com.jbase.jrcs-jrclient-api) with parameters of type [JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs")**

| Constructor |  Description |
| --- | --- |
| [JDynArray](./../../jdynarray-jrclient-api)([JDynArray](./../../jdynarray-jrclient-api "class in com.jbase.jrcs") src) | Constructs a dynamic array from another dynamic array |

Back to [Class Use](./../README.md)

  
<PageFooter />
