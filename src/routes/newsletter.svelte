<script>
import Story from "../components/Story.svelte";


</script>

<body>
   <header>
       <h2>Trends Newsletter</h2>
   </header>
   
   <section id="container">
       <Story headline="Battle of the Talking Heads"
       date="Sunday, July 17, 2022"
       location="Lofty Spaces | 816 Montgomery St. | Dallas, TX" 
       story="The longest running barber battle in the Midwest is on tour. Come see the best in the game compete on stage
        + showcases & more!!" />
   </section>
</body>


<style>
    body {
        margin: 2rem 1rem;
    }

    #container {
        display: flex;
        flex-direction: column;
        gap: 2rem;

    }
</style>