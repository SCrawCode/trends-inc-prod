<script>
import Button from "../components/Button.svelte";
import Card from "../components/Card.svelte";

   
</script>

<svelte:head>
    <title>Trends Inc.</title>
</svelte:head>

    <header class="header">
        <h1>Trends Inc.</h1>
        <div class="header-links">
            <a href="/newsletter"><Button name="Newsletter" /></a>
            <a href="/directory"><Button name="Directory" /></a>
        </div>
    </header>
    
    <section id="about">
        <h3>About Trends Inc.</h3>
        <p>Every discoverer needs a scout and when it comes to Kansas City&apos;s Black businesses,
            you can count on Trends Inc. to find exactly what you need! Take a look at our ever growing business directory
            or check out the newsletter to find out what&apos;s going on with Trends Inc.
          </p> 
    </section>

    <section id="services">
        <h3>Trends Services</h3>
            <ul>
                <li><Card pic="../static/careslogo.png" link="foundation" name="Trends Cares Foundation"/></li>
                <li><Card pic="../static/shoplogo.png" link="barbershop" name="Trends GMC Barbershop"/></li>
                <li><Card pic="../static/incncologo.png" link="clothes-shop" name="Trends Inc. & Company"/></li>
            </ul>
    </section>

    <section id="podcast">
        <h3>Trends Podcast</h3>
            <iframe src="" frameborder="0" title="Trends Podcast">Podcast Frame</iframe>
    </section>

    <section id="contact">
        <h3>Contact Trends Inc.</h3>
            <ul>
                <li><p>Phone: (xxx) xxx-xxxx</p></li>
                <li><p>Email: Trends@domain.com</p></li>
                <li><p>Phone: xxxx Trends Address St.</p></li>
            </ul>
    </section>


<style>

    * {
        margin: 0;
        text-align: center;
    }

    .header {
        margin: 0;
        padding: 0px 20px;
        background: url(../static/KC.png);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: 50vh;
        position: relative;
    }

    .header-links {
        display: flex;
        gap: 1rem;
        justify-content: center;
        padding-top: 40vh;
    }

    .header h1 {
        position: absolute;
        top: 4rem;
        left: 50vw;
        transform: translateX(-50%);
        color: white;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, .25);
    }

    #about {
        margin: 5rem 2rem;
        padding: .5rem;
        display: flex;
        flex-direction: column;
        gap: 1.5rem;
    }

    #podcast {
        margin: 5rem 2rem;
        background-color: rgba(0, 0, 0, .25);
        border-radius: 15px;
        padding: 1.5rem;
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }

    #podcast h3 {
        color: white;
    }

    h3 {
        font-size: larger;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, .25);
    }

    ul {
        padding: 0;
    }

    li {
        list-style: none;
    }

    #services {
        margin: 5rem 0;
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }

    #services ul {
        display: flex;
        flex-direction: column;
    }

    #contact {
        margin: 5rem 2rem;
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }

    #contact ul {
        display: flex;
        flex-direction: column;
        gap: .5rem;
    }
</style>