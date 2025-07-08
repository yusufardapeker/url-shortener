<script setup>
import { defineProps } from "vue";

defineProps({
	variety: {
		type: String,
		default: "rounded",
	},

	onClickFunction: Function,
});
</script>

<template>
	<button :class="`btn ${variety}`" @click="onClickFunction">
		<slot></slot>
	</button>
</template>
