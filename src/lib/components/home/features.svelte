<script>
	import { ChevronRight } from 'lucide-svelte';
</script>

<section class="p-golden-lg bg-[var(--green-secondary)] py-8 text-pretty md:py-18">
	<!-- Import -->

	<div class="mx-auto max-w-6xl">
		<div class="min-h-[450px]">
			<!-- Start Import -->
			<div class="gap-x-golden-md grid grid-cols-12 items-start">
				<h2
					class="col-span-12 text-left text-xl font-bold md:col-span-8 md:mb-6 md:text-2xl lg:text-3xl"
				>
					Your Private Pinterest, Instagram Saves, or Bookmarks Collection
				</h2>
				<div
					class="col-span-12 flex flex-col items-end text-base md:col-span-5 md:px-0 md:pt-8 md:pb-12 md:text-xl"
				>
					<p class="">
						Add SingleFile saves, Evernote exports, images, videos, audio, and PDFs files. Saved
						locally, available even when the webpage disappears.
					</p>

					<div class="mt-4">
						<a href="/docs/03_import_notes">
							<button class="btn btn-ghost"
								>See How Imports Work <ChevronRight size={18} />
							</button>
						</a>
					</div>
				</div>

				<div class="p-golden-md col-span-12 col-start-1 md:col-span-6 md:col-start-7">
					<figure class="">
						<img
							class="dark:border-base-content/10 rounded-lg border shadow-md dark:hidden"
							src="images/import-dark.png"
							alt=""
						/>
					</figure>
					<figure class="">
						<img class="hidden rounded-lg shadow-md dark:block" src="images/import.png" alt="" />
					</figure>
				</div>
			</div>
			<!-- End Import -->

			<!-- Discover -->
			<div class="gap-x-golden-md mt-12 grid grid-cols-12 items-start">
				<div
					class="p-golden-md order-3 col-span-12 col-start-1 md:order-1 md:col-span-7 md:col-start-1"
				>
					<figure>
						<img
							class="dark:border-base-content/10 rounded-lg border shadow-md dark:hidden"
							src="images/discover-dark.png"
							alt=""
						/>
						<figure>
							<img
								class="hidden rounded-lg shadow-md dark:block"
								src="images/discover.png"
								alt=""
							/>
						</figure>
					</figure>
				</div>

				<div
					class="my-golden-md md:m-golden-xl order-1 col-span-12 md:order-2 md:col-span-5 md:col-start-8 md:mt-0"
				>
					<h2 class="text-right text-xl font-bold md:mt-10 md:text-left md:text-2xl lg:text-3xl">
						Discover Notes Based on Algorithm
					</h2>
					<div
						class="flex flex-col text-right text-base md:my-4 md:items-end md:text-left md:text-xl"
					>
						<p>Notes are presented based on rating, upvotes, and how recently they were viewed. Filter them by notebook or tags.</p>
						<div class="mt-4">
							<a href="/docs/06_discover">
								<button class="btn btn-ghost"
									>See How Discover Work <ChevronRight size={18} />
								</button>
							</a>
						</div>
					</div>
				</div>
			</div>
			<!-- End Discover -->
		</div>
	</div>
</section>
