<script>
    import {goto} from "$app/navigation";
    const clickHandler = () => {
        goto("/products");
    }
</script>
<h1>Welcome to SvelteKit</h1>
<a href="/docs">Docs</a><br>
<a href="/products">Products</a>
<br>
<button on:click={clickHandler}>Go to products</button>