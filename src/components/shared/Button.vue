<script setup>
import { defineProps } from "vue";

defineProps({
	variety: {
		type: String,
		default: "rounded",
	},
});
</script>

<template>
	<button :class="`btn ${variety}`">
		<slot></slot>
	</button>
</template>
