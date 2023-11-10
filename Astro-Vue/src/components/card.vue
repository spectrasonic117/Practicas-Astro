<template>
	<div class="card">
		<h2>{{ title }}</h2>
		<p>{{ content }}</p>
		<!-- <input
			type="text"
			v-model="text" /> -->
	</div>
</template>

<script>
export default {
	name: "Card",
	data() {
		return {
			title: "Card Title",
			content: "Lorem ipsum dolor sit...",
		};
	},
};
</script>

<style>
.card {
	width: 170px;
	padding: 30px;
	background: green;
	border-radius: 16px;
	color: white;
}
</style>
