<script>
    export let label = "Button";
    export let primary = false;
    export let onClick;
</script>

<button class="btn" class:btn-primary={primary}
    on:click={onClick}
>{label}</button>