# org.json Skill

Use this skill to work with Norm module `org.json` version 3. Use only declarations listed below.

## `org.json`

Source: `JSONArray.norm`

### `JSONArray`

```norm
class JSONArray implements Iterable<Any>
```

#### `JSONArray`

```norm
JSONArray(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `get`

```norm
Any? get(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Any?`

#### `getBoolean`

```norm
Boolean getBoolean(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `getDouble`

```norm
Double getDouble(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Double`

#### `getInt`

```norm
Integer getInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `getJSONArray`

```norm
JSONArray? getJSONArray(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `JSONArray?`

#### `getJSONObject`

```norm
JSONObject? getJSONObject(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `JSONObject?`

#### `getLong`

```norm
Long getLong(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Long`

#### `getNumber`

```norm
Number? getNumber(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Number?`

#### `getString`

```norm
String? getString(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `isNull`

```norm
Boolean isNull(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `join`

```norm
String? join(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `length`

```norm
Integer length()
```

Returns: `Integer`

#### `opt`

```norm
Any? opt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Any?`

#### `optBoolean`

```norm
Boolean optBoolean(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `optBoolean`

```norm
Boolean optBoolean(Integer arg0, Boolean arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Boolean`

Returns: `Boolean`

#### `optDouble`

```norm
Double optDouble(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Double`

#### `optDouble`

```norm
Double optDouble(Integer arg0, Double arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Double`

Returns: `Double`

#### `optInt`

```norm
Integer optInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `optInt`

```norm
Integer optInt(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Integer`

#### `optJSONArray`

```norm
JSONArray? optJSONArray(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `JSONArray?`

#### `optJSONArray`

```norm
JSONArray? optJSONArray(Integer arg0, JSONArray? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `JSONArray?`

Returns: `JSONArray?`

#### `optJSONObject`

```norm
JSONObject? optJSONObject(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `JSONObject?`

#### `optJSONObject`

```norm
JSONObject? optJSONObject(Integer arg0, JSONObject? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `JSONObject?`

Returns: `JSONObject?`

#### `optLong`

```norm
Long optLong(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Long`

#### `optLong`

```norm
Long optLong(Integer arg0, Long arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Long`

Returns: `Long`

#### `optNumber`

```norm
Number? optNumber(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Number?`

#### `optNumber`

```norm
Number? optNumber(Integer arg0, Number? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Number?`

Returns: `Number?`

#### `optString`

```norm
String? optString(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

#### `optString`

```norm
String? optString(Integer arg0, String? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `String?`

Returns: `String?`

#### `put`

```norm
JSONArray? put(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0, Double arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Double`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0, Long arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Long`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0, Any? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Any?`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Integer arg0, Boolean arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Boolean`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `JSONArray?`

#### `put`

```norm
JSONArray? put(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `JSONArray?`

#### `remove`

```norm
Any? remove(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Any?`

#### `similar`

```norm
Boolean similar(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `toList`

```norm
JavaList<Any>? toList()
```

Returns: `JavaList<Any>?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `toString`

```norm
String? toString(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

### `jsonArrayNew`

```norm
JSONArray jsonArrayNew()
```

Returns: `JSONArray`

### `jsonArrayNew`

```norm
JSONArray jsonArrayNew(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONArray`

## `org.json`

Source: `JSONObject.norm`

### `JSONObject`

```norm
class JSONObject
```

#### `JSONObject`

```norm
JSONObject(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `get`

```norm
Any? get(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Any?`

#### `getBoolean`

```norm
Boolean getBoolean(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `getDouble`

```norm
Double getDouble(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Double`

#### `getInt`

```norm
Integer getInt(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Integer`

#### `getJSONArray`

```norm
JSONArray? getJSONArray(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONArray?`

#### `getJSONObject`

```norm
JSONObject? getJSONObject(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONObject?`

#### `getLong`

```norm
Long getLong(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Long`

#### `getNumber`

```norm
Number? getNumber(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Number?`

#### `getString`

```norm
String? getString(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `has`

```norm
Boolean has(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `isNull`

```norm
Boolean isNull(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `keySet`

```norm
JavaSet<String>? keySet()
```

Returns: `JavaSet<String>?`

#### `keys`

```norm
Iterator<String>? keys()
```

Returns: `Iterator<String>?`

#### `length`

```norm
Integer length()
```

Returns: `Integer`

#### `names`

```norm
JSONArray? names()
```

Returns: `JSONArray?`

#### `opt`

```norm
Any? opt(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Any?`

#### `optBoolean`

```norm
Boolean optBoolean(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `optBoolean`

```norm
Boolean optBoolean(String? arg0, Boolean arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Boolean`

Returns: `Boolean`

#### `optDouble`

```norm
Double optDouble(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Double`

#### `optDouble`

```norm
Double optDouble(String? arg0, Double arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Double`

Returns: `Double`

#### `optInt`

```norm
Integer optInt(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Integer`

#### `optInt`

```norm
Integer optInt(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `Integer`

#### `optJSONArray`

```norm
JSONArray? optJSONArray(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONArray?`

#### `optJSONArray`

```norm
JSONArray? optJSONArray(String? arg0, JSONArray? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `JSONArray?`

Returns: `JSONArray?`

#### `optJSONObject`

```norm
JSONObject? optJSONObject(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONObject?`

#### `optJSONObject`

```norm
JSONObject? optJSONObject(String? arg0, JSONObject? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `JSONObject?`

Returns: `JSONObject?`

#### `optLong`

```norm
Long optLong(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Long`

#### `optLong`

```norm
Long optLong(String? arg0, Long arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Long`

Returns: `Long`

#### `optNumber`

```norm
Number? optNumber(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Number?`

#### `optNumber`

```norm
Number? optNumber(String? arg0, Number? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Number?`

Returns: `Number?`

#### `optString`

```norm
String? optString(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `optString`

```norm
String? optString(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

#### `put`

```norm
JSONObject? put(String? arg0, Double arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Double`

Returns: `JSONObject?`

#### `put`

```norm
JSONObject? put(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `JSONObject?`

#### `put`

```norm
JSONObject? put(String? arg0, Long arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Long`

Returns: `JSONObject?`

#### `put`

```norm
JSONObject? put(String? arg0, Any? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Any?`

Returns: `JSONObject?`

#### `put`

```norm
JSONObject? put(String? arg0, Boolean arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Boolean`

Returns: `JSONObject?`

#### `remove`

```norm
Any? remove(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Any?`

#### `similar`

```norm
Boolean similar(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `toMap`

```norm
JavaMap<String, Any>? toMap()
```

Returns: `JavaMap<String, Any>?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `toString`

```norm
String? toString(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

### `jsonObjectFieldGetNull`

```norm
Any? jsonObjectFieldGetNull()
```

Returns: `Any?`

### `jsonObjectNew`

```norm
JSONObject jsonObjectNew()
```

Returns: `JSONObject`

### `jsonObjectNew`

```norm
JSONObject jsonObjectNew(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JSONObject`

### `jsonObjectQuote`

```norm
String? jsonObjectQuote(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `jsonObjectStringToValue`

```norm
Any? jsonObjectStringToValue(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Any?`

### `jsonObjectWrap`

```norm
Any? jsonObjectWrap(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Any?`

