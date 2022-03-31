<script>
    import Button from '../components/Button.svelte'
</script>

<svelte:head><title>Trends Cares Foundation</title></svelte:head>


    <header class="header">
        <h2>Trends Cares Foundation</h2>
    </header>

    <section id="about">
        <h3>About Us</h3>
        <p>Trends Care Foundation is set up to help children of bereaved parents.
             Our goal is to help these surviving children financially with moral support and guidance.
             When tragedy happens, our goal is to make sure that no child is left behind.
             The mission is to help them with Growth and Development by Mentoring them throughout their influential adolescence.
        </p>
    </section>

    <section id="join">
        <h3>Join Trends Cares Foundation</h3>
        <form action="" class="join">
            <input type="text" name="name" id="name" placeholder="Full Name">
            <input type="email" name="email" id="email" placeholder="Email">
            <input type="tel" name="number" id="number" placeholder="Phone">
            <div class="submit">
                <Button name="Join" back="black" color="white" /> 
            </div>
        </form>
    </section>

    <section id="donate">
        <!-- Shopify API -->
    </section>


<style>
    * {
        margin: 1.5rem;
    }

    .header {
        margin: 0;
        padding: 0px 20px;
        background: url(../static/help.png);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: 50vh;
        position: relative;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 1.5rem;
    }

    .header h2 {
        color: white;
        text-align: center;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, .75);
    }

    #about {
        padding: .25rem;
        text-align: center;
    }

    form {
        display: flex;
        flex-direction: column;
        gap: .1rem;
        margin: 1rem auto;
    }

    input {
        background-color: white;
        padding: .75rem;
        border: 2px solid black;
        border-radius: 9999px;
    }

    .submit {
        margin: 0 auto;
    }
</style>