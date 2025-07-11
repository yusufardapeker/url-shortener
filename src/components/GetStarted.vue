<script setup>
import Button from "./shared/Button.vue";
import boostBgMobile from "@/images/bg-boost-mobile.svg";
import boostBgDesktop from "@/images/bg-boost-desktop.svg";
</script>

<template>
	<section id="get-started">
		<picture>
			<source media="(min-width: 376px)" :srcset="boostBgDesktop" />
			<img :src="boostBgMobile" alt="background-img" class="bg-img" />
		</picture>

		<h2 class="title">Boost your links today</h2>
		<Button>Get Started</Button>
	</section>
</template>
