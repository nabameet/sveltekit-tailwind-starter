<script>
	let count = 0;
	const increment = () => count++;
</script>

<button
	class="mx-10 py-1 hehe text-2xl bg-gray-900 shadow-sm text-white px-6 rounded"
	on:click={increment}
>
	Clicks: {count}
</button>
