<script setup>
const color = 'blue';
</script>

<template>
	<div class="board">
		<div :class="`${color}`">sup</div>
		<div v-bind:class="`${color}`">hi</div>
	</div>
</template>

<style scoped></style>
