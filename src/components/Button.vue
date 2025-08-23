<script setup></script>

<template>
	<button class="btn">
		<!-- named slot -->
		<slot name="icon"></slot>
		<slot name="iconText"></slot>
		<!-- slot receives any tags and text (span with text) that Button components wraps -->
		<slot></slot>
	</button>
</template>

<!-- attribute 'scoped' adds to the html tag additional data-attribute with component id
and applies styles for these components only -->
<style scoped>
.btn {
	font-size: 4rem;
}
</style>
