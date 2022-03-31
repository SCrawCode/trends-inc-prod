<script>
    export let headline = '';
    export let date = '';
    export let location = '';
    export let story = ''; 
</script>


<div class="container">
    <div class="headline">
        <h3>{headline}</h3>
        <h5>{ date }</h5>
        <h5>{ location }</h5>
    </div>

    <div class="story">
        <p>{story}</p>
    </div>
</div>


<style>
    .container {
        margin: 2rem;
        box-shadow: 1px 2px 4px rgba(0, 0, 0, .25);
        padding: 1rem;
    }

    .headline {
        border-bottom: 1px solid rgba(0, 0, 0, .5);
    }

    .story p {
        font-size: smaller;
    }

</style>