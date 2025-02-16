<script setup>
import Hero from "@/components/Hero.vue";
import HomeCards from "@/components/HomeCards.vue";
import JobsListings from "@/components/JobListings.vue";
</script>

<template>
	<Hero title="Test" />
	<HomeCards />
	<JobsListings :limit="3" :showButton="true" />
</template>
