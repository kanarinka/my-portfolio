<script>
    import projects from '$lib/projects.json';
    import Project from "$lib/Project.svelte";

</script>

<h1>kanarinka</h1>
    <p>kanarinka is a hacker mama, neighborhood cartographer, and ultimate frisbee player.</p>
    <p>This is not kanarinka</p>
    <img src="images/Important Man with seagull head.jpg" width="50%" alt="A statue of an important man with a seagull on his head"/> 
    <h1>Latest Projects</h1>
    <div class="projects">
        {#each projects.slice(0,3) as p }
            <Project data={p} hLevel=2/>
        {/each}
        
    </div>