Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# VectorValue class
Represents a vector type in Firestore documents. Create an instance with .

 VectorValue

<b>Signature:</b>

```typescript
export declare class VectorValue 
```

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [isEqual(other)](./firestore_lite.vectorvalue.md#vectorvalueisequal) |  | Returns <code>true</code> if the two VectorValue has the same raw number arrays, returns <code>false</code> otherwise. |
|  [toArray()](./firestore_lite.vectorvalue.md#vectorvaluetoarray) |  | Returns a copy of the raw number array form of the vector. |

## VectorValue.isEqual()

Returns `true` if the two VectorValue has the same raw number arrays, returns `false` otherwise.

<b>Signature:</b>

```typescript
isEqual(other: VectorValue): boolean;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  other | [VectorValue](./firestore_lite.vectorvalue.md#vectorvalue_class) |  |

<b>Returns:</b>

boolean

## VectorValue.toArray()

Returns a copy of the raw number array form of the vector.

<b>Signature:</b>

```typescript
toArray(): number[];
```
<b>Returns:</b>

number\[\]
