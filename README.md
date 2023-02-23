# Vector2

> Utility class written in TypeScript for dealing with 2D vectors in an immutable way.

## Why
I made this to better understand vectors and I like working with vectors that behave like primitive types (like in Godot), where the result is always a new value.

## Usage

```ts
// Adding two vectors together.
const a = new Vector(10, 10);
const b = new Vector(50, 80);

// Adding `a` to `b` will not modify `a`, it returns a new vector.
const result = a.add(b);

// Methods can be chained.
const scaled = a.add(b).normalized().scale(10);
```
