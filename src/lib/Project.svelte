<script>
    export let data = {};
    export let hLevel = {};

 </script>
<article>
    <svelte:element this={"h" + hLevel}>{ data.title }</svelte:element>
    <img src={data.image} alt="">
    <p>{data.description}</p>
</article>


