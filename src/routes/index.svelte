<script context="module" lang="ts">
	export const ssr = false;
</script>

<script lang="ts">
	import Editor from '$lib/Tiptap/Editor.svelte';
</script>

<svelte:head>
	<title>Codent</title>
</svelte:head>

<!-- <Monaco /> -->
<Editor documentId="example-document" />
