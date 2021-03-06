[yesno-http](../README.md) > ["filtering/matcher"](../modules/_filtering_matcher_.md)

# External module: "filtering/matcher"

## Index

### Interfaces

* [ISerializedHttpPartialDeepMatch](../interfaces/_filtering_matcher_.iserializedhttppartialdeepmatch.md)

### Type aliases

* [MatchFn](_filtering_matcher_.md#matchfn)
* [RequestQuery](_filtering_matcher_.md#requestquery)
* [ResponseQuery](_filtering_matcher_.md#responsequery)

### Functions

* [match](_filtering_matcher_.md#match)

---

## Type aliases

<a id="matchfn"></a>

###  MatchFn

**Ƭ MatchFn**: *`function`*

#### Type declaration
▸(serialized: *[ISerializedHttp](../interfaces/_http_serializer_.iserializedhttp.md)*): `boolean`

**Parameters:**

| Name | Type |
| ------ | ------ |
| serialized | [ISerializedHttp](../interfaces/_http_serializer_.iserializedhttp.md) |

**Returns:** `boolean`

___
<a id="requestquery"></a>

###  RequestQuery

**Ƭ RequestQuery**: *`object`*

#### Type declaration

___
<a id="responsequery"></a>

###  ResponseQuery

**Ƭ ResponseQuery**: *`object`*

#### Type declaration

___

## Functions

<a id="match"></a>

###  match

▸ **match**(fnOrPartialMatch: * [ISerializedHttpPartialDeepMatch](../interfaces/_filtering_matcher_.iserializedhttppartialdeepmatch.md) &#124; [MatchFn](_filtering_matcher_.md#matchfn)*): `function`

Curried function to determine whether a query matches an intercepted request.

Query objects must be a deep partial match against the intercepted request.

RegEx values are tested for match.

**Parameters:**

| Name | Type |
| ------ | ------ |
| fnOrPartialMatch |  [ISerializedHttpPartialDeepMatch](../interfaces/_filtering_matcher_.iserializedhttppartialdeepmatch.md) &#124; [MatchFn](_filtering_matcher_.md#matchfn)|

**Returns:** `function`

___

