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
| `rfc`       | A functional component               |
| `rfci`      | A functional component w/ interfaces |
| `rfct`      | A functional component w/ types      |

**Usage:**

1. Type `rfc`.
2. Press `Enter`.
3. Name your component.

### 1. React Functional Component (`rfc`)

```typescript
export function $1() {
  return $2;
}
```

### 2. React Functional Component with Interfaces(`rfci`)

```typescript
interface I$1 {
  $2;
}

export function $1() {
  return $4;
}
```

### 3. React Functional Component with types(`rfct`)

```typescript
type $1Props = {
  $2;
};

export function $1(props: $1Props) {
  return $4;
}
```

### Download it [here](https://marketplace.visualstudio.com/items?itemName=Lukeskw.ReactFunctionalSnippetForVSCODE)

### License

This extension is licensed under the MIT License.
