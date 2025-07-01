<script setup>
import heroIllsutration from "@/images/illustration-working.svg";
import Button from "./shared/Button.vue";
</script>

<template>
	<div id="hero">
		<img :src="heroIllsutration" class="hero-img" alt="working-illustration" />

		<div class="text-content container">
			<h1>More than just shorter links</h1>
			<p class="hero-description">
				Build your brand's recognition and get detailed insights on how your links are performing.
			</p>

			<Button>Get Started</Button>
		</div>
	</div>
</template>
