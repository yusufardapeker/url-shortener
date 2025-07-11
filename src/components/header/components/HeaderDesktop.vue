<script setup>
import logo from "@/images/logo.svg";
import Button from "@/components/shared/Button.vue";
</script>

<template>
	<div class="header-desktop">
		<img :src="logo" alt="logo" class="logo" />

		<ul class="links">
			<li class="link">Features</li>
			<li class="link">Pricing</li>
			<li class="link">Resources</li>
		</ul>

		<div class="user-actions">
			<a href="#" class="login-link">Login</a>
			<Button>Sign Up</Button>
		</div>
	</div>
</template>
