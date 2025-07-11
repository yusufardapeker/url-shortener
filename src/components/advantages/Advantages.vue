<script setup>
import { FeaturesData } from "./constants";
</script>

<template>
	<section id="features">
		<div class="container">
			<div class="introduction">
				<h2 class="title">Advanced Statistics</h2>
				<p class="description">
					Track how your links are performing across the web with our advanced statistics dashboard.
				</p>
			</div>

			<div class="features-wrapper">
				<div v-for="feature in FeaturesData" class="feature">
					<div class="img-wrapper">
						<img :src="feature.img" :alt="feature.img" class="img" />
					</div>

					<h3 class="title">{{ feature.title }}</h3>
					<p class="description">{{ feature.description }}</p>
				</div>
			</div>
		</div>
	</section>
</template>
