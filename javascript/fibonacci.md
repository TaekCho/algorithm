<h1>Fibonacci Numbers</h1>

```
let fiboFinder = function (num) {
  switch (num) {
    case 0:
      return [0];
      break;
    case 1:
      return [0, 1];
      break;
    default:
      const fib = [0, 1];
      for (i = 2; i < num; i++) {
        fib[i] = fib[i - 1] + fib[i - 2];
      }
      return fib;
  }
};
```
