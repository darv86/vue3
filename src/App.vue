<script setup>
import Button from './components/Button.vue';

const iconText = 'iconText';
</script>

<template>
	<div class="board">
		<Button>
			<!-- data for the named slot should be placed inside the template tag
			with a v-slot attribute and slot name -->
			<!-- <template v-slot:icon>+</template> -->
			<template #icon>+</template>
			<!-- dynamic name for a slot (slot name interpolation) -->
			<template #[iconText]>Add </template>
			<span class="btn__span">Button</span>
		</Button>
	</div>
</template>

<style scoped></style>
