# JRemoteResponse (jremote API)

<PageHeader />

## Class JRemoteResponse

All Implemented Interfaces:[JBaseSerializable](./../../io/jbaseserializable-(jremote-api) "interface in com.jbase.jremote.io")Direct Known Subclasses:[ConvResponse](./../convresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [DateTimeResponse](./../datetimeresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [EISMetaDataResponse](./../eismetadataresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [InputOutputResponse](./../inputoutputresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [JediResponse](./../jediresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [JExecuteResults](./../../jexecuteresults-(jremote-api) "class in com.jbase.jremote"), [MonitoringResponse](./../monitoringresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [ReadCommonResponse](./../readcommonresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [SelectListFetchResponse](./../selectlistfetchresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [SetPropertiesResponse](./../setpropertiesresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [StatementFetchResponse](./../statementfetchresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [SubroutineResponse](./../subroutineresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [SwitchAccountResponse](./../switchaccountresponse-(jremote-api) "class in com.jbase.jremote.protocol"), [TransactionResponse](./../transactionresponse-(jremote-api) "class in com.jbase.jremote.protocol")
* * *


```
public abstract class JRemoteResponse
extends Response
```

### Nested Class Summary

- Nested classes/interfaces inherited from interface com.jbase.jremote.io.JBaseSerializable
    - `JBaseSerializable.TYPE`






### Constructor Summary


| Constructor and Description<br> |
| --- |
| `JRemoteResponse()` <br> |






### Method Summary


| Modifier and Type<br> | Method and Description<br> |
| --- | --- |
| `int`<br> | `getVersion()` <br> |


- Methods inherited from class java.lang.Object
    - `clone, equals, finalize, getClass, hashCode, notify, notifyAll, toString, wait, wait, wait`
- Methods inherited from interface com.jbase.jremote.io.JBaseSerializable
    - `getType, readObject, writeObject`

### Constructor Detail

#### JRemoteResponse

```
public JRemoteResponse()
```





### Method Detail

#### getVersion

```
public int getVersion()
```

Back to [jRemote API](../../../../jremote-api/README.md)



  
<PageFooter />
