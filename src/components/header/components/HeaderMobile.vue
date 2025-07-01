<script setup>
import { ref } from "vue";
import logo from "@/images/logo.svg";
import Button from "@/components/shared/Button.vue";

const showMobileNavigation = ref(false);

const toggleMobileNavigation = () => {
	showMobileNavigation.value = !showMobileNavigation.value;
};
</script>

<template>
	<div class="header-mobile">
		<img :src="logo" alt="logo" />
		<i @click="toggleMobileNavigation" class="fa-solid fa-bars"></i>
	</div>
	<div v-if="showMobileNavigation" class="mobile-navigation">
		<ul class="links">
			<li class="link">Features</li>
			<li class="link">Pricing</li>
			<li class="link">Resources</li>
		</ul>
		<div class="user-actions">
			<a href="#">Login</a>
			<Button>Sign Up</Button>
		</div>
	</div>
</template>
