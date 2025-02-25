<script>
	import Nested from './nested.svelte';

	let value = $state(0);
</script>

<p>The current value is {value}</p>

<Nested
	increment={() => value+= 1}
	decrement={() => value -= 1}/>
