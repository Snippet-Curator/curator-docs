<script lang="ts">
	import { ChevronRight } from 'lucide-svelte';
</script>

<div class="mx-auto max-w-6xl pt-28 pb-10 md:min-h-screen">
	<!-- Title -->
	<h1 class="mb-2 text-center text-4xl font-bold md:text-5xl lg:text-6xl">Curator</h1>

	<!-- Description -->
	<div class="mx-auto max-w-3xl text-center">
		<p class="mb-golden-lg text-lg">Organize and re-discover your internet saves</p>
		<a href="/docs" class="flex items-center gap-x-2 text-base"
			><button class="btn btn-primary mx-auto">Get Started<ChevronRight size={18} /></button>
		</a>
	</div>
	<!-- Image -->
	<div class="m-golden-xl mt-10">
		<figure>
			<img
				class="hidden rounded-md shadow-xl dark:block"
				alt="hero light"
				src="images/frontpage.png"
			/>
		</figure>
		<figure>
			<img
				class="rounded-md shadow-xl dark:hidden"
				alt="hero dark"
				src="images/frontpage-dark.png"
			/>
		</figure>
	</div>
</div>
