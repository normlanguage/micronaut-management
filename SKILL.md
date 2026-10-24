# micronaut.management Skill

Use this skill to work with Norm module `micronaut.management` version 4. Use only declarations listed below.

## `micronaut.management`

Source: `JavaArrays.norm`

### `JavaStringArray`

```norm
class JavaStringArray
```

#### `JavaStringArray`

```norm
JavaStringArray(JavaStringArrayBindingToken token)
```

Parameters:

- `token`: `JavaStringArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
String? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `String?`

#### `set`

```norm
Void set(Integer index, String? value)
```

Parameters:

- `index`: `Integer`
- `value`: `String?`

Returns: `Void`

### `javaStringArrayNew`

```norm
JavaStringArray javaStringArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaStringArray`

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Delete.norm`

### `Delete`

```norm
annotation Delete implements FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `description`

```norm
String description
```

Type: `String`

#### `produces`

```norm
List<String> produces
```

Type: `List<String>`

#### `Delete`

```norm
Delete(String? description, List<String>? produces)
```

Parameters:

- `description`: `String?`
- `produces`: `List<String>?`

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Endpoint.norm`

### `Endpoint`

```norm
annotation Endpoint implements TypeTarget, RuntimeRetention
```

#### `defaultConfigurationId`

```norm
String defaultConfigurationId
```

Type: `String`

#### `defaultEnabled`

```norm
Boolean defaultEnabled
```

Type: `Boolean`

#### `defaultSensitive`

```norm
Boolean defaultSensitive
```

Type: `Boolean`

#### `id`

```norm
String id
```

Type: `String`

#### `prefix`

```norm
String prefix
```

Type: `String`

#### `value`

```norm
String value
```

Type: `String`

#### `Endpoint`

```norm
Endpoint(String? defaultConfigurationId, Boolean? defaultEnabled, Boolean? defaultSensitive, String? id, String? prefix, String? value)
```

Parameters:

- `defaultConfigurationId`: `String?`
- `defaultEnabled`: `Boolean?`
- `defaultSensitive`: `Boolean?`
- `id`: `String?`
- `prefix`: `String?`
- `value`: `String?`

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Read.norm`

### `Read`

```norm
annotation Read implements FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `description`

```norm
String description
```

Type: `String`

#### `produces`

```norm
List<String> produces
```

Type: `List<String>`

#### `Read`

```norm
Read(String? description, List<String>? produces)
```

Parameters:

- `description`: `String?`
- `produces`: `List<String>?`

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Selector.norm`

### `Selector`

```norm
annotation Selector implements ParameterTarget, RuntimeRetention, InheritedAnnotation
```

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Sensitive.norm`

### `Sensitive`

```norm
annotation Sensitive implements FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `defaultValue`

```norm
Boolean defaultValue
```

Type: `Boolean`

#### `property`

```norm
String property
```

Type: `String`

#### `value`

```norm
Boolean value
```

Type: `Boolean`

#### `Sensitive`

```norm
Sensitive(Boolean? defaultValue, String? property, Boolean? value)
```

Parameters:

- `defaultValue`: `Boolean?`
- `property`: `String?`
- `value`: `Boolean?`

## `micronaut.management.endpoint.annotation`

Source: `endpoint/annotation/Write.norm`

### `Write`

```norm
annotation Write implements FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `consumes`

```norm
List<String> consumes
```

Type: `List<String>`

#### `description`

```norm
String description
```

Type: `String`

#### `produces`

```norm
List<String> produces
```

Type: `List<String>`

#### `Write`

```norm
Write(List<String>? consumes, String? description, List<String>? produces)
```

Parameters:

- `consumes`: `List<String>?`
- `description`: `String?`
- `produces`: `List<String>?`

## `micronaut.management.endpoint.health`

Source: `endpoint/health/DetailsVisibility.norm`

### `DetailsVisibility`

```norm
enum DetailsVisibility
```

#### `ANONYMOUS`

```norm
ANONYMOUS
```

#### `AUTHENTICATED`

```norm
AUTHENTICATED
```

#### `NEVER`

```norm
NEVER
```

## `micronaut.management.health.indicator`

Source: `health/indicator/HealthCheckType.norm`

### `HealthCheckType`

```norm
enum HealthCheckType
```

#### `LIVENESS`

```norm
LIVENESS
```

#### `READINESS`

```norm
READINESS
```

