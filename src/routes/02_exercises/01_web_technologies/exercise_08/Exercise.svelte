<script>
const my_name= "Raly";
const fruits="apples";
const veget=["salad", "cucumber", "peas"];

let names = ["John", "Paul", "Bibi"]
</script>

<p>My name is {my_name} ! </p>
<p>My favorite fruits are {fruits} </p>

<p>My favorable vagetables are {veget}. How do I put a space? </p>

<h3>Looping list names</h3>
<ul>
{#each names as name}
<li>{name}</li>
{/each}
</ul>