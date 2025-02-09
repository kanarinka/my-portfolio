<svelte:head>
	<title>Contact me</title>
</svelte:head>

<h1>Contact</h1>
<form action="mailto:kanarinka@gmail.com" method="GET">
    <label for="email">Your email:<input name="email" type="email"/></label>
    <label for="subject">Subject:<input name="subject"/></label>
    <label for="body">Your message:<textarea name="body"></textarea></label>
    <button>Submit</button>
</form>
