Reproduction for https://github.com/microsoft/TypeScript/issues/50533

Steps:

1. Run yarn install
2. Run yarn build — everything works
3. Run yarn build again —  

Fails with —

```
error TS5055: Cannot write file '/Users/skanodia/dev/typescript-bug-entrypoints/dist/types/classnames.d.ts' because it would overwrite input file.
```