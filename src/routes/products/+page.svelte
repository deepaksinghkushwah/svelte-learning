<script>
  const products = [
    { id: 1, name: "Product 1",slug: "product-1" },
    { id: 2, name: "Product 2",slug: "product-2" },
    { id: 3, name: "Product 3",slug: "product-3" },
  ];
</script>

<h1>Producs Page</h1>
{#each products as item}
  <a href="/products/{item.slug}">{item.name}</a>
  <br />
{/each}