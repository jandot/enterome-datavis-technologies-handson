<script>
	let count=0;

	function incrementCount(){
		count += 1;
	}
</script>



<div>
<button on:click={incrementCount}>>
 Clicked {count} {count ===1 'time' : 'times'}
</button>

</div>


	let clicked = false;
	{if clicked = false}


<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	<!--  -->
</div>