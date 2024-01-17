<script>
	import WithComment from "$lib/WithComment.svelte";
	import NoComment from "$lib/NoComment.svelte";
	import NoWhitespaces from "$lib/NoWhitespaces.svelte";
	import WithSpan from "$lib/WithSpan.svelte";
</script>

<span>With html comment:<WithComment /></span>
<br />
<br />
<span>No html comment:<NoComment /></span>
<br />
<br />
<span>No whitespaces + html comment:<NoWhitespaces /></span>
<br />
<br />
<span>`span` instead of a comment:<WithSpan /></span>
