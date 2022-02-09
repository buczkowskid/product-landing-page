<template>
	<section class="spec">
		<div class="spec-container">
			<SpecificationSectionTable />
			<SpecificationSectionDetails />
		</div>
	</section>
</template>

<script>
import SpecificationSectionTable from "./SpecificationSectionTable.vue";
import SpecificationSectionDetails from "./SpecificationSectionDetails.vue";
export default {
	components: {
		SpecificationSectionTable,
		SpecificationSectionDetails,
	},
};
</script>

<style>
.spec {
	background-color: #ffffff;
}
.spec-container {
	display: flex;
	flex-direction: column;
	margin: 0 30rem;
	overflow-x: auto;
}

/* MEDIA */
@media (max-width: 1200px) {
	.spec-container {
		margin: 0 auto;
		padding: 0 2.5rem;
	}
}

@media (max-width: 320px) {
	.spec-container {
		padding: 0.5rem;
	}
}
</style>
