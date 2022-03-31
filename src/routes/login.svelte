<script>
import Button from "../components/Button.svelte";

</script>
<body>
    <h3>Register Your Company to Our Directory</h3>
        <form action="">
            <input type="text" name="company" id="company" placeholder="Company Name">
            <input type="text" placeholder="Company Email">
            <input type="tel" name="number" id="numbeer" placeholder="Company Number">
            <input type="text" name="site" id="site" placeholder="Company Website">
            <div class="submit">
                <Button name="Register" back="black" color="white" /> 
            </div>
        </form>
</body>


<style>
    body {
        margin: 1rem;
    }

    form {
        display: flex;
        flex-direction: column;
        gap: .5rem;
        margin: 2rem auto;
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