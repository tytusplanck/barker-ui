<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		display: block;
		margin-left: auto;
		margin-right: auto;
		width: 50%;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Barker</title>
</svelte:head>

<h1>Welcome human!</h1>
<div>
	<img alt='Puppy' src='puppy.jpeg'>
</div>
<a href="create">Add a Dog</a>
