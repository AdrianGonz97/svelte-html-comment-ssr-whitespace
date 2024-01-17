<script>
	import WithComment from "$lib/WithComment.svelte";
	import NoComment from "$lib/NoComment.svelte";
	import NoWhitespaces from "$lib/NoWhitespaces.svelte";
	import WithSpan from "$lib/WithSpan.svelte";
</script>

<span>With comment:<WithComment /></span>
<br />
<span>No comment:<NoComment /></span>
<br />
<span>No whitespaces:<NoWhitespaces /></span>
<br />
<span>`span` instead of a comment:<WithSpan /></span>
