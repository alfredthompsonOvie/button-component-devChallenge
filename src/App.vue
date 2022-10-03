<template>
	<h1 class="title">buttons</h1>

	<section class="buttons__wrapper">
		<div class="btn__container">
			<base-button>
				<span> Default </span>
			</base-button>
		</div>

		<div class="btn__container">
			<base-button variant="outline">
				<span> Default </span>
			</base-button>
		</div>

		<div class="btn__container">
			<base-button variant="text">
				<span> Default </span>
			</base-button>
		</div>

		<div class="btn__container">
			<base-button variant="disableShadow">
				<span> Default </span>
			</base-button>
		</div>

		<section class="section disableWrapper">
			<div class="btn__container">
				<base-button variant="disable" disabled="true">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="disable--text" disabled="true">
					<span> disabled </span>
				</base-button>
			</div>
		</section>

		<!-- icon -->
		<section class="section icon">
			<div class="btn__container">
				<base-button variant="local_grocery_store">
					<span></span>
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="local_grocery_store--alt">
					<span></span>
					<span> Default </span>
				</base-button>
			</div>
		</section>
		<!-- size -->
		<section class="section size">
			<div class="btn__container">
				<base-button variant="sm">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="md">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="lg">
					<span> Default </span>
				</base-button>
			</div>
		</section>
		<!-- color -->
		<section class="section colors">
			<div class="btn__container">
				<base-button variant="default">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="primary">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="secondary">
					<span> Default </span>
				</base-button>
			</div>
			<div class="btn__container">
				<base-button variant="danger">
					<span> Default </span>
				</base-button>
			</div>
		</section>
	</section>

	<p class="copyright">
		created by <a href="https://github.com/alfredthompsonOvie" class="myLink" target="_blank"> alfred thompson ovie</a> -
		<a href="https://devchallenges.io/challenges/ohgVTyJCbm5OZyTB2gNY" target="_blank">devChallenges.io</a>
	</p>
</template>

<script>
import BaseButton from "@/components/BaseButton.vue";
export default {
	components: {
		BaseButton,
	},
};
</script>

<style></style>
