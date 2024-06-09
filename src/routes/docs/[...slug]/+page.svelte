
<script>
    import {page} from "$app/stores";
    const urlParams = $page.params.slug.split("/");
</script>
<h1>this is docs</h1>

{#each urlParams as param}
    {param} <br>
{/each}