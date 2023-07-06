# isSubset

첫 번째 배열이 두 번째 배열의 부분 집합인지 여부를 검사합니다.

```typescript
function isSubset(a: unknown[], b: unknown[]): boolean;
```

# Examples

```typescript
isSubset([], [1, 2, 3]); // true
isSubset([1, 2], [1, 2, 3]); // true
isSubset([3, 2, 1], [1, 2, 3]); // true
isSubset(['v', 'u'], ['v', 'a', 'l', 'u', 'e']); // true
isSubset([1, 4], [1, 2, 3]); // false
```