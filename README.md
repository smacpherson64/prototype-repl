# Prototype

Testing REPL vs run for deno info on modules:

```
console.log('mainModule url', Deno.mainModule)
console.log('import.meta.url', import.meta.url)
console.log('import.meta.main', import.meta.main)
```

## Running `deno run main.ts`

- mainModule url file:///Users/seth/Projects/personal/prototype-repl/main.ts
- import.meta.url file:///Users/seth/Projects/personal/prototype-repl/main.ts
- import.meta.main true

## Running `deno repl --eval-file=main.ts`

- mainModule url file:///Users/seth/Projects/personal/prototype-repl/$deno$repl.ts
- SyntaxError: Cannot use 'import.meta' outside a module
- SyntaxError: Cannot use 'import.meta' outside a module
