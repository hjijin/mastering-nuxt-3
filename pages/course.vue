<template>
	<div class="flex flex-col items-center w-full h-full min-h-screen p-12 bg-gray-100">
		<div class="mb-12 prose">
			<h1>
				<span class="font-medium">
					Course:
					<span class="font-bold">Mastering Nuxt 3</span>
				</span>
			</h1>
		</div>

		<div class="flex flex-row justify-center flex-grow">
			<div class="prose mr-4 p-8 bg-white rounded-md min-w-[20ch] max-w-[30ch] flex flex-col">
				<h3 class="font-bold">Chapters</h3>
			</div>

			<div class="prose p-12 bg-white rounded-md w-[65ch]">
				<NuxtPage />
			</div>
		</div>
	</div>
</template>

<script setup>
// const { chapters } = useCourse();
</script>