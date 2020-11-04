# vuehtml

Syntax Highlight for Vue HTML inside `template strings` and `.html files`.

## Features

Use it in `template string` as:

```js
/* vue-html */ `
  <div class="discount">
    <span>Discount Code:</span>
    <input
      type="text"
      placeholder="Code"
      @keyup.enter="applyDiscount($event)"
    />
  </div>
  <button :disabled="product.stock === 0" @click="addToCart()">
    Agregar al carrito
  </button>
`;
```

> Note: This extension will automatically add syntax highlight inside .html files
