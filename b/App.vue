<template>
	<div class="amazing">Hello {{ vue }}!</div>
</template>

<script lang="ts">
export default {
	data() {
		return {
			vue: "Vue",
		};
	},
};
</script>

<style>
.amazing {
	color: blue;
}
</style>
