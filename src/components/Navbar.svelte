<nav>
    <ul class="navbar">
        <li class="logo"><a href="/"><img src='../../static/Logo.png' alt=""></a></li>
        <li class="item"><a href="#about">About</a></li>
        <li class="item"><a href="#services">Services</a></li>
        <li class="item"><a href="/login">Register</a></li>
    </ul>
</nav>


<style>
    .navbar {
        display: flex;
        justify-content: flex-end;
        align-items: center;
        gap: .5rem;
        padding: .75rem 1.5rem;
        border-bottom: 1px solid rgba(0, 0, 0, .25);
        background-color: black;
        margin: 0;
        height: 2.5rem;
    }

    .logo {
        margin-right: auto;
        padding: 5px 0 0 2.5px;
    }

    .logo img {
        width: 32px;
    }

    .logo img:hover {
        cursor: pointer;
    }

    .item {
        padding: .5rem;
        border-radius: 5px;
    }

    .item:hover {
        background-color: rgba(255, 255, 255, .25);
    }

    li {
        list-style: none;
    }


    a {
        text-decoration: none;
        color: white;
        font-size: smaller;
        font-family: 'Raleway', sans-serif;
    }
</style>