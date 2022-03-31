<script>
    export let name = '';
    export let back = '';
    export let color = '';
</script>

<button type="button" style="background: {back}; color: {color}" >
    { name }
</button>

<style>
    button {
        background-color: white;
        border: 2px solid white;
        border-radius: 25px;
        padding: 8px;
        width: 120px;
        font-weight: 900;
    }

    button:hover {
        background-color: black;
        color: white;
        cursor: pointer;
    }
</style>