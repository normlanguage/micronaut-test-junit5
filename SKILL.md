# micronaut.test.junit5 Skill

Use this skill to work with Norm module `micronaut.test.junit5` version 3. Use only declarations listed below.

## `micronaut.test.junit5`

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

## `micronaut.test.junit5`

Source: `MicronautTest.norm`

### `MicronautTest`

```norm
annotation MicronautTest implements TypeTarget, FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `application`

```norm
Class<?> application
```

Type: `Class<?>`

#### `deduceEnvironment`

```norm
Boolean deduceEnvironment
```

Type: `Boolean`

#### `environments`

```norm
List<String> environments
```

Type: `List<String>`

#### `packages`

```norm
List<String> packages
```

Type: `List<String>`

#### `propertySources`

```norm
List<String> propertySources
```

Type: `List<String>`

#### `rebuildContext`

```norm
Boolean rebuildContext
```

Type: `Boolean`

#### `resolveParameters`

```norm
Boolean resolveParameters
```

Type: `Boolean`

#### `rollback`

```norm
Boolean rollback
```

Type: `Boolean`

#### `startApplication`

```norm
Boolean startApplication
```

Type: `Boolean`

#### `transactionMode`

```norm
TransactionMode transactionMode
```

Type: `TransactionMode`

#### `transactional`

```norm
Boolean transactional
```

Type: `Boolean`

#### `MicronautTest`

```norm
MicronautTest(Class<?>? application, Boolean? deduceEnvironment, List<String>? environments, List<String>? packages, List<String>? propertySources, Boolean? rebuildContext, Boolean? resolveParameters, Boolean? rollback, Boolean? startApplication, TransactionMode? transactionMode, Boolean? transactional)
```

Parameters:

- `application`: `Class<?>?`
- `deduceEnvironment`: `Boolean?`
- `environments`: `List<String>?`
- `packages`: `List<String>?`
- `propertySources`: `List<String>?`
- `rebuildContext`: `Boolean?`
- `resolveParameters`: `Boolean?`
- `rollback`: `Boolean?`
- `startApplication`: `Boolean?`
- `transactionMode`: `TransactionMode?`
- `transactional`: `Boolean?`

## `micronaut.test.junit5.io.micronaut.test.annotation`

Source: `io/micronaut/test/annotation/TransactionMode.norm`

### `TransactionMode`

```norm
enum TransactionMode
```

#### `SEPARATE_TRANSACTIONS`

```norm
SEPARATE_TRANSACTIONS
```

#### `SINGLE_TRANSACTION`

```norm
SINGLE_TRANSACTION
```

