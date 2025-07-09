<script setup>
import Button from "./shared/Button.vue";
import boostBgMobile from "@/images/bg-boost-mobile.svg";
</script>

<template>
	<section id="get-started">
		<img :src="boostBgMobile" alt="background-img" class="bg-img" />

		<h2 class="title">Boost your links today</h2>
		<Button>Get Started</Button>
	</section>
</template>
