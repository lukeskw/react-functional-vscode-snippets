# React Functional Snippets

Welcome to the React Functional Components (RFC) snippets for VS Code! This set of snippets is designed to boost your productivity when creating React functional components. Whether you're working with JavaScript, JSX, TypeScript, or TSX, these snippets will help you quickly scaffold functional components with different configurations.

### Navigation Guide

When working with multiple placeholders ($1, $2, $3, $4) in the snippets, you can navigate between them using the Tab key. Here's a quick guide:

1. After typing the snippet prefix, press Tab to move to the next placeholder.
2. Keep pressing Tab to cycle through the placeholders.
3. Press Shift + Tab to move to the previous placeholder.

### Snippets

| **Snippet** | **Renders**                          |
| ----------- | ------------------------------------ |
| `cl`        | `console.log()` with variable        |
| `cls`       | `console.log()` with string          |
| `rfc`       | A functional component               |
| `rfci`      | A functional component w/ interfaces |
| `rfct`      | A functional component w/ types      |
| `ust`       | React Use State snippet              |
| `ustt`      | Typed React Use State snippet        |
| `usef`      | React Use Effect snippet             |
| `usefr`     | React Use Effect with Return snippet |

**Usage:**

1. Type the snippet prefix.
2. Press `Enter` to use the snippet.
3. Follow the instructions to fill in placeholders.

> Note: With Hooks, you should need to press Tab 2x to capitalize correctly.

### 1. `console.log()` with variable (`cl`)

```javascript
console.log($1);
```

### 2. `console.log()` with string (`cls`)

```javascript
console.log("$1");
```

### 3. React Functional Component (`rfc`)

```typescript
export function $1() {
  return $2;
}
```

### 4. React Functional Component with Interfaces(`rfci`)

```typescript
interface I$1 {
  $2;
}

export function $1() {
  return $4;
}
```

### 5. React Functional Component with types(`rfct`)

```typescript
type $1Props = {
  $2;
};

export function $1(props: $1Props) {
  return $4;
}
```

### 6. React Use State Snippet(`ust`)

```typescript
const [ $1, set${1:capitalize} ] = useState($2);
```

### 7. Typed React Use State Snippet(`ustt`)

```typescript
const [ $1, set${1:capitalize} ] = useState<$2>($3);
```

### 8. React Use Effect Snippet(`usef`)

```typescript
useEffect(() => {
  $1;
}, [$2]);
```

### 9. React Use State with Return Snippet(`usefr`)

```typescript
useEffect(() => {
  $1;
  return () => {
    $2;
  };
}, [$3]);
```

### Download it [here](https://marketplace.visualstudio.com/items?itemName=Lukeskw.ReactFunctionalSnippetForVSCODE)

### License

This extension is licensed under the MIT License.
