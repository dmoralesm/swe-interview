# JavaScript Tricky Questions

## Question 1

What is the ouput of next block code execution?

```js
function a() {
  return { 
    a: true 
  };
}

function b() {
  return 
  { 
    b: true 
  };
}

console.log(a());
console.log(b());
```

Answer
```
{ a: true }
undefined
```

Why?

[Automatic Semicolon Insertion](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Automatic_semicolon_insertion)

Try it online: https://repl.it/@dmoralesm/js-asi