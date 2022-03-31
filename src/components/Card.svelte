<script>
    export let name = '';
    export let link = '';
    export let pic = '';
</script>

<div class="card-container">
    <a href={link}>
        <div class="card-head">
            <img src={pic} alt="Card-Img">
        </div>
        <div class="card-foot">
            <h4><a href={link}>{name}</a></h4>
        </div>
    </a>
</div>

<style>
    .card-container {
        box-shadow: 0px 1px 2.5px rgba(0, 0, 0, .15);
        border: 1px solid rgba(0, 0, 0, .1);
        border-radius: 7.5px;
        width: 60%;
        margin: .5rem auto;
    }

    .card-container:hover {
        box-shadow: 0px 1px 4px rgba(0, 0, 0, .25);
    }

    .card-head {
        height: 100%;
        width: 100%;
    }

    .card-head img {
        width: 100%;
        height: 160px;
        border-radius: 7.5px;
    }

    h4 {
        text-shadow: 1px 1px 1px rgba(0, 0, 0, .25);
    }

    a {
        text-decoration: none;
        color: black;
    }
</style>