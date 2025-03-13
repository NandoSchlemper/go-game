<script lang="ts">
    let { children } = $props();
</script>

<div class="navbar">
    <nav>
        <button>Inventory</button>
        <button>Magic</button>
        <button>Profile</button>
    </nav>
</div>

{@render children()}

<style>
    .navbar {
        padding-left: 200px;
    }
</style>
