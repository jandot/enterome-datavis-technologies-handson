<script>
 let name="World"
</script>

<h2>Hello {name}</h2>


<script>
	let src = '/tutorial/image.gif';
</script>

<img src={src} alt="a man dances">

<p>This is a paragraph.</p>

<style>
	/* Write your CSS here */
	p{
		color: blue;
		font-family: 'Comic Sans MS', cursive;
		font-size: 3em;
	}
</style>


<script>
	import Nested from './Nested.svelte'
</script>	

<p>This is a paragraph.</p>

<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>

<Nested/>